---
name: deployments
about: Run playbooks and deployments and for all applications
title: 'Run deployments for the workcycle starting on [INSERT DATE HERE]'
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
- [ ] [Staging](https://bibdata-staging.princeton.edu/)
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
#### Mudd DB
- [ ] [Staging](https://library-staging.princeton.edu/mudd-dbs)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://library.princeton.edu/mudd-dbs)
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
- [ ] [Staging](https://library-staging.princeton.edu/byzantine/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://library.princeton.edu/byzantine/)
  - [ ] Playbook
  - [ ] Deploy
#### Friends of the Library
- [ ] [Staging](https://fpul-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://fpul.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
#### Library Website
- [ ] [Staging](https://library-staging.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] Before deploying to production check [Check if end users have changed any settings](https://github.com/pulibrary/pul_library_drupal/wiki/Sync-a-Feature(s)-from-Production)
- [ ] [Production](https://library.princeton.edu/)
  - [ ] Playbook
  - [ ] Deploy - Before deploying to production check [Check if end users have changed any settings](https://github.com/pulibrary/pul_library_drupal/wiki/Sync-a-Feature(s)-from-Production)
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
#### Special Collections
- [ ] [Staging](https://library-staging.princeton.edu/special-collections/)
  - [ ] Playbook
  - [ ] Deploy
- [ ] [Production](https://library.princeton.edu/special-collections/)
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
