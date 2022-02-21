# Steps to handle dependabot PRs

You can find dependabot PRs by checking [github](https://github.com/issues?q=is%3Aopen+archived%3Afalse+mentions%3Adependabot+user%3Apulibrary)

1. Check to make sure CI passes on the dependabot PR.
1. Compare the date of the PR with the date of the last commit
to `main`.  If there have been commits since dependabot made
its PR, trigger a rebase by commenting ``@dependabot rebase``
1. Copy the name of the dependabot branch.
1. In the #robots channel on slack, deploy the dependabot branch
to staging or qa.
    * If it needed to rebase, CI may not have finished yet, so 
    you might have to use `pulbot deploy!` if the
    typical `pulbot deploy` command doesn't work.
    * You can find a list of pulbot's configured apps and
    environments at https://github.com/pulibrary/pulbot/blob/main/apps.json
1. After the branch is deployed, test the application to make
sure all is well.
1. If everything looks good, approve the PR and merge it.
