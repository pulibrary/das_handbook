These are services and applications a dev on the team needs to have to support
our operations.

# Github

All developers need a github profile handle with a public key to push and pull code to our two Princeton github communities. SSH Access to all servers is also through the use of this public key. 

# Princeton SSO Account (i.e. DUO, Your University Account, the netid account)
* University Email (Set-up via Campus HR Onboarding)
* VPN (GlobalProtect Client) -- [procedure here under "Installing GlobalProtect Software"](https://workcontinuity.princeton.edu/remoteaccess)
* Google Drive (student developers already have an account; staff should [follow these instructions](https://princeton.service-now.com/service/kb_search.do?id=1111))
* Libanswers https://princeton.libapps.com/ (Patron facing tickets) - Kevin can grant access (student developers can skip this)
* SN@P (Staff facing tickets) - Request access from Tracy Hall in Operations (student developers can skip this)
* Approvals (Library Travel Requests) - account created automatically
* Lastpass (need to be added to various Shared ITIMS folders once an account exists - https://informationsecurity.princeton.edu/LastPass)

# Externally Hosted Catalog Related Applications
* Alma (ask the Alma managers in the #alma-dacs channel.  Students can skip this until they need to work on a ticket that involves alma)
    - Alma Prod - https://princeton.alma.exlibrisgroup.com/SAML
    - Alma Sandbox - https://princeton-psb.alma.exlibrisgroup.com/SAML
* SCSB (ReCAP Middleware)
    - Prod https://scsb.recaplib.org/
    - https://uat-recap.htcinc.com.htcinc.com 
* POD (Platform for Open Data) https://pod.stanford.edu/ (Kevin or Esmé can create an account for you. Students can skip this until they need to work on a ticket that involves POD.)

# Atlas Systems Applications

Staff clients for all three of these Atlas systems. They are accessible only via Windows Remote Desktop when connected to following designated machines lib-ares-cli1, lib-ares-cli2. An account for a dev will need to be created manually in each of the three systems. Students can skip this.
* Aeon (Special Collections Reading Room Management - Hosted Locally)
    - Public web app https://lib-aeon.princeton.edu/aeon/
* ILLiad (InterLibrary Loan - Hosted Locally)
    - Public web app at https://lib-illiad.princeton/illiad/
* ARES (Hosted by Atlas Systems)
    - Web Application is embedded in campus Canvas LMS

# Locally Hosted Applications with Staff Accounts

## Ruby on Rails Applications

### Lockers and Study Spaces

- [Lockers production](https://lockers-and-study-spaces.princeton.edu)
- [Lockers staging](https://lockers-and-study-spaces-staging.princeton.edu)

### DSS
- [DSS production](https://dss.princeton.edu/catalog)
- [DSS staging](https://dss-staging.princeton.edu/catalog)

### Repec

- [Repec production](https://repec-prod.princeton.edu/).  You can SSH into the server and use the [rails console steps in the README](https://github.com/pulibrary/repecwp/) to add a new user.

## Drupal Websites

To add a new developer to a drupal site, a current team member
who is an admin can follow these steps:

1. Go to '/user'
2. Log in
3. Go to 'People'
4. Select 'Add CAS user(s)'
5. Add the netid
6. Press 'Create new account'
7. Edit the new user to have the 'administrator' role.    

### Library Main Website

- [Library website production](https://library.princeton.edu)
- [Library website staging](https://library-staging.princeton.edu)

### Special Collections Department Website
- [Special collections production](http://library.princeton.edu/special-collections)
- [Special collections staging](http://library-staging.princeton.edu/special-collections)

### Research Data Service Website
- [RDSS production](https://researchdata.princeton.edu)
- [RDSS production](https://researchdata-staging.princeton.edu)


### ReCAP Facility Website
- [ReCAP production ](https://recap.princeton.edu)
- [ReCAP staging](https://recap-staging.princeton.edu)

### Friends of the Princeton Library Website
- [Friends production](https://fpul.princeton.edu)
- [Friends staging](https://fpul-staging.princeton.edu)

## Php applications

### Princeton and Slavery (craftcms application)
- [Princeton and Slavery production](https://slavery.princeton.edu)
- [Princeton and Slavery staging](https://slavery-staging.princeton.edu)

# Other External Services

* [Ex Libris Developers Network](https://developers.exlibrisgroup.com/) (One of the Alma team will add you to the "Princeton" Team)
* [Datadog](https://www.datadoghq.com/) monitoring and alerts.  Another team member can invite you.
* [CircleCI](https://circleci.com/) access via Github Account.  You will have access automatically when you are added to the pulibrary github organization.
* [Amazon AWS](https://princeton.edu/aws).  Francis can add you.
* [Honeybadger](https://www.honeybadger.io/). Another team member can invite you.
* [Dubbot](https://princeton.dubbot.com/).
* [Ansible Tower](https://ansible-tower.princeton.edu/)   
   * Contact the Ops team to add their IDs to the active directory group for Tower access.  
