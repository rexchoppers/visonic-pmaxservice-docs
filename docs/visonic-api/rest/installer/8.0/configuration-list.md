# /configuration_list

## Name
/configuration_list

## Description
This method returns a list of configurations downloaded from the panel (5)

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /configuration_list`

## Example Response
```json
[
  {
    "date": "2025-01-08T00:23:33+0200",
    "verified_at": "2025-01-08T00:23:33+0200",
    "id": 39,
    "backup": false
  },
  {
    "date": "2025-01-10T18:26:20+0200",
    "verified_at": "2025-01-10T18:26:20+0200",
    "id": 40,
    "backup": false
  },
  {
    "date": "2025-01-23T15:15:49+0200",
    "verified_at": "2025-01-23T15:15:49+0200",
    "id": 41,
    "backup": false
  },
  {
    "date": "2025-01-23T15:43:10+0200",
    "verified_at": "2025-01-23T15:43:10+0200",
    "id": 42,
    "backup": false
  },
  {
    "date": "2025-01-23T16:47:10+0200",
    "verified_at": "2025-01-23T16:47:10+0200",
    "id": 43,
    "backup": false
  },
  {
    "date": "2025-01-23T16:49:45+0200",
    "verified_at": "2025-01-23T16:49:45+0200",
    "id": 44,
    "backup": false
  },
  {
    "date": "2025-01-23T17:32:42+0200",
    "verified_at": "2025-01-23T17:32:42+0200",
    "id": 45,
    "backup": false
  },
  {
    "date": "2025-01-23T17:41:35+0200",
    "verified_at": "2025-01-23T17:41:35+0200",
    "id": 46,
    "backup": false
  }
]
```
