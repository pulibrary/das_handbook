These are services and applications a dev on the team needs to have to support
our operations.

# Github

All developers need a github profile handle with a public key to push and pull code to our two Princeton github communities. SSH Access to all servers is also through the use of this public key. 

# Pulbot

Pulbot is used deploy applications via a slack channel integration. The slack channel is the private channel "robots". You need to add a PR to the pulbot github repo in this fashion to add a new user: https://github.com/pulibrary/pulbot/pull/108/files. The unique ID is the slack member ID for the accoount that is being attached to the bot. 

# Princeton SSO Account (i.e. DUO, Your University Account, the netid account)
* University Email (Set-up via Campus HR Onboarding)
* VPN, aka Secure Remote Access (GlobalProtect Client Preferred)
* Google Drive (follow instructions at https://princeton.service-now.com/service/kb_search.do?id=1111)
* Libanswers https://princeton.libapps.com/ (Patron facing tickets) - Kevin can grant access
* SN@P (Staff facing tickets) - Request access from Tracy Hall in Operations
* Approvals (Library Travel Requests) - account created automatically
* Lastpass (need to be added to various Shared ITIMS folders once an account exists - https://informationsecurity.princeton.edu/LastPass) 

# Externally Hosted Catalog Related Applications
* Alma
    - Alma Prod - https://princeton.alma.exlibrisgroup.com/SAML
    - Alma Sandbox - https://princeton-psb.alma.exlibrisgroup.com/SAML
* SCSB (ReCAP Middleware)
    - Prod https://scsb.recaplib.org/
    - https://uat-recap.htcinc.com.htcinc.com 
* POD (Platform for Open Data) https://pod.stanford.edu/

# Atlas Systems Applications

Staff clients for all three of these Atlas systems. They are accessible only via Windows Remote Desktop when connected to following designated machines lib-ares-cli1, lib-ares-cli2. An account for a dev will need to be created manually in each of the three systems. 
* Aeon (Special Collections Reading Room Management - Hosted Locally)
    - Public web app https://lib-aeon.princeton.edu/aeon/
* ILLiad (InterLibrary Loan - Hosted Locally)
    - Public web app at https://lib-illiad.princeton/illiad/
* ARES (Hosted by Atlas Systems)
    - Web Application is embedded in campus Canvas LMS

# Locally Hosted Applications with Staff Accounts
* Ruby on Rails Applications
    - Lockers and Study Spaces
    - https://lockers-and-study-spaces.princeton.edu
    - https://lockers-and-study-spaces-staging.princeton.edu
    - DSS
    - https://dss.princeton.edu/catalog
    - https://dss-staging.princeton.edu/catalog
    - Repec
    - https:/repec-prod.princeton.edu/
* Drupal Websites
    - Library Main Website
    - https://library.princeton.edu
    - https://library-staging.princeton.edu
    - Special Collections Department Website
    - http://library.princeton.edu/special-collections
    - http://library-staging.princeton.edu/special-collections
    - Research Data Service Website
    - https://researchdata.princeton.edu
    - https://researchdata-staging.princeton.edu
    - ReCAP Facility Website
    - https://recap.princeton.edu
    - https://recap-staging.princeton.edu
    - Friends of the Princeton Library Website
    - https://fpul.princeton.edu
    - https://fpul-staging.princeton.edu
* Other Tools
    - Princeton and Slavery (craftcms application)
    - https://slavery.princeton.edu
    - https://slavery-staging.princeton.edu


# Other External Services

* Ex Libris Developers Network (One of the Alma team add you to the "Princeton" Team)
* Datadog - monitoring and alerts https://www.datadoghq.com/ 
* CircleCI - https://circleci.com/ access via Github Account 
* Amazon AWS - https://princeton.edu/aws 
* Honeybadger - https://www.honeybadger.io/
