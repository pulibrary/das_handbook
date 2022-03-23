# Steps to handle dependabot PRs

You can find dependabot PRs by checking [github](https://github.com/search?q=repo%3Apulibrary%2Ffirestone_locator+repo%3Apulibrary%2Flockers_and_study_spaces+repo%3Apulibrary%2Frepecwp+repo%3Apulibrary%2Fmudd-dbs+repo%3Apulibrary%2Fdiscoveryutils+repo%3Apulibrary%2Frecap+repo%3Apulibrary%2Fbibdata+repo%3Apulibrary%2Fspecial_collections+repo%3Apulibrary%2Ffriends_of_pul+repo%3Apulibrary%2Fresearchdata+repo%3Apulibrary%2FDSS+repo%3Apulibrary%2Frequests+repo%3Apulibrary%2Flib_jobs+repo%3Apulibrary%2Fbyzantine_translations+repo%3Apulibrary%2Fpul_library_drupal+repo%3Apulibrary%2Fapprovals+repo%3Apulibrary%2Fgeaccirc+repo%3Apulibrary%2Forangelight+repo%3Apulibrary%2Faspace_helpers+label%3Adependencies+state%3Aopen&type=Issues&ref=advsearch&l=&l=)

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
