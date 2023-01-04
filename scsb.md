## Checking the SCSB API

1. Go to the [SCSB swagger API console](https://scsb.recaplib.org:9093/swagger-ui/index.html)
1. Press the authorize button
1. Enter the `SCSB_AUTH_KEY` from the orangelight or bibdata app_configs
1. Press the close button
1. To test the availability response:
    1. Open the shared-collection-rest-controller section
    1. Open the `/sharedCollection/bibAvailabilityStatus` POST request
    1. Press the "Try it out" button
    1. For the bibliographic ID, use the SCSB id without the SCSB- prefix (e.g. for SCSB-11259399, you would enter 11259399)
    1. For the institutionId, you can use `scsb` or a more specific institution.
    1. Press the execute button
