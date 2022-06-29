# Runner role

The runner role switches off between team members each week.  The runner should be somebody who is planning to be in for the whole week.

## Initial setup

Before serving as a runner, do the following steps to get set up:

1. Make sure that honeybadger email notifications are turned on for the DACS team projects.  It can be helpful to [turn off honeybadger user notifications for projects we don't support](https://app.honeybadger.io/users/edit#notifications). Manage how often you will receive emails [digest email settings](https://app.honeybadger.io/users/edit#digest).
1. In the honeybadger UI, open a project and search for `created.after:"7 days ago" -is:resolved -is:ignored`.
1. Click the bookmark icon to bookmark this search.

## Triaging new honeybadger errors

Go to the honeybadger dashboard daily and look at honeybadger activity for DACS applications.  You can quickly review activity using the bookmarked search.  There is typically no need to review honeybadger activity from previous weeks.

Also triage any new honeybadger errors that come in via email.

Note: for some of the projects, the staging and qa environments are included in honeybadger.

### Errors that need immediate attention

Notify the rest of the team on slack.

### All other errors

Don't use the "Create Issue" button in honeybadger, since the history can be purged in honeybadger and we can miss important context.  Instead, follow these steps:

* Create an issue in the github repo.
* Add the honeybadger link in the issue's description
* Copy over the failing code block from honeybadger into the issue, not just the line numbers (since they can change)
* In honeybadger, add a comment with the link to the github issue
* As you troubleshoot, add any updates as a github comment
