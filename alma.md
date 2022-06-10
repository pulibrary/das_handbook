# Alma is our Library Services Platform

## Access

### User Login
* Production Login URL - https://princeton.alma.exlibrisgroup.com/SAML
* Sandbox Login URL - https://princeton-psb.alma.exlibrisgroup.com/SAML

### API Base URLs

* Production
* Sandbox

## Active Integrations

### NCIP (Resource Sharing Integrations)

SCSB and other systems that facilitate resource sharing leverage this interface. 

### Alma Publishing

Daily Job that publishes added/updated/delete records to the Library Catalog

### Peoplesoft Financials

Three daily jobs that keep Alma in sync with the University financial system. 

* Voucher Feed
* Fund Adjustment
* Invoice Status (Payment Confirmation)

### Person Feed

Daily job that adds/updates patrons in Alma based on active PUL community members in Peoplesoft.

### Bursar Feed 

Two Part weekly job that deals with fine payments, credits, and account blocks. 

### POD Export Feed

Daily job that adds/updates/deletes Princeton metadata in POD.

### SCSB SubmitCollection Feed

Daily job that adds/updates/deletes Princeton metadata in SCSB. 

### Recap Partner Renewal Job

Daily job that processes renewal requests for parter SCSB items loaned to Princeton patrons. Also leverages NCIP. 