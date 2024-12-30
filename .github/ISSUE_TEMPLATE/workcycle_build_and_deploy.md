---
name: deployments
about: Run playbooks and deployments and for all applications
title: 'Run deployments for the week starting on [INSERT DATE HERE]'
labels: ['deployments', 'playbooks']
assignees: ''

---
## List of applications
### Ruby applications
#### Allsearch API
- [ ] [Staging](https://allsearch-api-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://allsearch-api.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Approvals
- [ ] [Staging](https://approvals-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://approvals.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Bibdata
- [ ] [Staging](https://bibdata-staging.lib.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [QA](https://bibdata-qa.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://bibdata.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### DSS
- [ ] [Staging](https://dss-staging.princeton.edu/catalog)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://dss.princeton.edu/catalog)
  - [ ] Playbook
  - [ ] Deploy
#### GEAC
- [ ] [Staging](https://geaccirc-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://geaccirc.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Lib Jobs
- [ ] [Staging](https://lib-jobs-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://lib-jobs.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
##### Aspace Helpers
Shares a server with lib-jobs, no separate playbook
- [ ] Staging (no front end)
  - [ ] Deploy
- [ ] Production (no front end)
  - [ ] Deploy
#### Lockers
- [ ] [Staging](https://lockers-and-study-spaces-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://lockers-and-study-spaces.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Orangelight
- [ ] [Staging](https://catalog-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [QA](https://catalog-qa.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://catalog.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### RePec
- [ ] [Staging](https://repec-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://repec-prod.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy

### Vue applications
#### Allsearch Frontend
- [ ] [Staging](https://allsearch-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://allsearch.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Static Tables
- [ ] [Staging](https://static-tables-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://static-tables-prod.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy

### Drupal PHP applications
#### Byzantine Translations
- [ ] [Staging](https://byzantine-staging.lib.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://byzantine.lib.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### ReCAP
- [ ] [Staging](https://recap-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://recap.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Research Data
- [ ] [Staging](https://researchdata-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://researchdata.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy

### Other (non-Drupal) PHP applications
#### Princeton and Slavery
Note: Private repository, cannot use Tower to deploy, must deploy from local environment
- [ ] [Staging](https://slavery-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://slavery.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Video Reserves
Note: Private repository, cannot use Tower to deploy, must deploy from local environment
- [ ] [Staging](https://videoreserves-staging.princeton.edu/hrc/vod/clip.php) (forwards to 'days of heaven')
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://videoreserves-prod.princeton.edu/hrc/vod/clip.php) (forwards to 'days of heaven')
  - [ ] Playbook
  - [ ] Deploy

#### Notes
[Documentation on how to run all the staging playbooks at once using different tags.](https://github.com/pulibrary/dacs_handbook/blob/main/maintenance.md)

[Ansible playbooks](https://github.com/pulibrary/princeton_ansible/tree/main/playbooks)
