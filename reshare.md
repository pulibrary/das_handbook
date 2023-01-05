# ReShare

## Search VuFind By Standard Identifier

### Search by ISN

```
curl --location --request GET '{{vufind_url}}/api/v1/search?lookfor={{ISN}}&type=ISN&sort=relevance&page=1&limit=20&prettyPrint=false&lng=en' \
--header 'language=en; ui=standard'
```

### Search by Title/Author Name

```
curl --location -g --request GET '{{vufind_url}}/api/v1/search?join=AND&lookfor0[]=dickens&type0[]=Author&lookfor0[]=dickens&type0[]=Title&sort=relevance&page=1&limit=20&prettyPrint=false&lng=en' \
--header 'language=en; ui=standard'
```

### Example Response

```
{
    "resultCount": 1,
    "records": [
        {
            "authors": {
                "primary": {
                    "Lehmann, Chris": []
                },
                "secondary": [],
                "corporate": []
            },
            "formats": [
                "Book"
            ],
            "id": "42607fd2-5823-4f89-8063-327ec5b8603b",
            "languages": [
                "English"
            ],
            "series": [
                {
                    "name": "Paradigm (Chicago, Ill.) ;",
                    "number": "7."
                }
            ],
            "subjects": [
                [
                    "Mass media and culture"
                ],
                [
                    "Mass media and culture."
                ],
                [
                    "Popular culture",
                    "United States"
                ],
                [
                    "Popular culture",
                    "United States."
                ],
                [
                    "Popular culture"
                ],
                [
                    "Popular culture."
                ],
                [
                    "United States"
                ],
                [
                    "United States."
                ]
            ],
            "title": "Revolt of the masscult /",
            "urls": []
        }
    ],
    "status": "OK"
}
```

## Checking Request Status

### Getting an Auth Token From Okapi

```
curl --location --request POST 'https://princeton-okapi.reshare.indexdata.com/authn/login' \
--header 'X-Okapi-Tenant: princeton' \
--header 'Content-Type: application/json' \
--data-raw '{
    "username": "{{UIN}}",
    "password": "{{password}}"
}'
```

### Auth Response

The Response will contain an x-okapi-token header that can be used to make authenticated requests to Okapi.

### Check Loan Status

```
curl --location --request GET '{{okapi_url}}/rs/patronrequests/{{request_id}}' \
--header 'X-Okapi-Token: {{okapi_token}}' \
--header 'X-Okapi-Tenant: {{tenant}}'
```

#### Pickup Locations

| Location Name        | Location Slug | LMS Location Code |
|----------------------|---------------|-------------------|
| Architecture Library | PUL_arch      | arch              |
| East Asian Library   | PUL_eastasian | eastasian         |
| Engineering Library  | PUL_engineer  | engineer          |
| Firestone Library    | PUL_firestone | firestone         |
| Lewis Library        | PUL_lewis     | lewis             |
| Mendel Music Library | PUL_mendel    | mendel            |
| Stokes Library       | PUL_stokes    | stokes            |


#### Example Location Data from Response
```
"resolvedPickupLocation": {
        "id": "a08ef905-0e95-4ac5-b691-c946829ab679",
        "slug": "PUL_firestone",
        "tags": [
            {
                "id": 8,
                "normValue": "pickup",
                "value": "pickup"
            }
        ],
        "lmsLocationCode": "firestone",
        "name": "Firestone Library",
        "type": {
            "id": "2c90bab7813f87b20181704c5cd10479"
        },
        "status": {
            "id": "2c90bab7813f87b20181704c5cd4047b",
            "value": "managed",
            "label": "Managed",
            "owner": {
                "id": "2c90bab7813f87b20181704c5cd3047a",
                "desc": "DirectoryEntry.Status",
                "internal": false
            }
        },
        "parent": {
            "id": "246cd946-56ef-5f40-aa2f-b1c5b89d3e07",
            "name": "Princeton University",
            "fullyQualifiedName": "Princeton University"
        },
        "tagSummary": "pickup",
        "symbolSummary": "No symbols",
        "fullyQualifiedName": "Princeton University / Firestone Library"
    }
```

