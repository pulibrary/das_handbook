# Runner role

## Honeybadger

Make sure that honeybadger email notifications are turned on, and investigate when you get an email.

Also, go to the honeybadger dashboard daily and look at honeybadger activity for DACS applications.  There is typically no need to review honeybadger activity from previous weeks.

Note: for some of the projects, the staging and qa environments are included in honeybadger.

### Errors that need immediate attention

Notify the rest of the team on slack.

### All other errors

Don't use the "Create Issue" button in honeybadger, since the history can be purged in honeybadger and we can miss important context.  Instead, follow these steps:

* Create an issue in the github repo.
* Add the honeybadger link in the issue's description
* Copy over the failing code block from honeybadger into the issue, not just the line numbers (since they can change)
* In honeybadger, add a comment with the link to the github action
* As you troubleshoot, add any updates as a github comment
