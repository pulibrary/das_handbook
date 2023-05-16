# Deploying code

We deploy code using [Ansible Tower](https://ansible-tower.princeton.edu/).  For general procedures on how to deploy code, please see [the documentation in pul-it-handbook](https://github.com/pulibrary/pul-it-handbook/blob/main/services/deployment.md).

There are a few processes specific to DACS:

* If you are deploying orangelight or bibdata, please select the `#orangelight` slack channel to receive the deployment notifications.
* If you need to deploy a specific branch for a longer period of time (for example, you are asking stakeholders for their feedback or running on a long process), let the team know in slack.

## Staging and QA environments

Orangelight and Bibdata have both a staging and a qa environment.

The QA environment is generally used to gather feedback from stakeholders.  This means it is kept stable at least temporarily for stakeholders to review new features, etc.

The staging environment is meant more for testing new features and bug fixes before deploying to production.  Staging allows developers to continue deploying new work while the QA env showcases completed, pre-release features.

The QA environments are connected to production versions of Alma, Figgy, and other services.  The staging environments tend to be connected to the staging versions of those other services.
