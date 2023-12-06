# ArchivesSpace
ArchivesSpace is our Archival Content Management System. It contains our archival data of record.

## Contacts:
* Product Owner: Will Clements
* Technical Lead: Regine Heberlein
* Governance: ArchivesSpace Operation Group (SC)
* Slack channel: #aspace_help
* github repo tracking our config options: https://github.com/pulibrary/aspace-config

## Active Integrations:
* Alma
  * [aspace2alma](https://github.com/pulibrary/aspace_helpers): 
  This integration is maintained in-house. It runs on lib_jobs (but is not a rails app) from the `aspace_helpers/reports/aspace2alma` directory. It sends collection-level records, holdings, and items to Alma.
  * [as_marcao plugin](https://github.com/hudmol/as_marcao): 
  This integration relies on a plugin made for us by Hudson Molonglo. It sends component records and holdings for select collections.
* [pulfalight](https://github.com/pulibrary/pulfalight): 
  hourly incremental update of the finding aids site
* [figgy](https://github.com/pulibrary/figgy): 
  digital repository persists DAOs to ArchivesSpace
* [abid](https://github.com/pulibrary/abid): 
  generates absolute identifiers and saves them to ArchivesSpace

## Login:
* contact Will Clements for an account
* Prod login: https://aspace.princeton.edu/staff/auth/cas
* Staging login: https://aspace-staging.princeton.edu/staff/auth/cas

## API:
* documentation: https://archivesspace.github.io/archivesspace/api/#introduction
* Prod base URL: https://aspace.princeton.edu/staff/api
* Staging base URL: https://aspace-staging.princeton.edu/staff/api

## Server support:
* Hosting institution: Lyrasis
* Email: support@lyrasis.zendesk.com
