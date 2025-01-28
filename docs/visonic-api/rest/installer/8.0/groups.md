# /groups

## Name
/groups

## Description
This method returns the groups the panel can become a part of. I am unsure what this provides at the moment.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /groups`

## Example Response
```json
[
  {
    "id": 1,
    "name": "Main Group",
    "description": "",
    "is_selected": false,
    "central_stations": []
  },
  {
    "id": 5,
    "name": "TestGroup",
    "description": "Only for the upgrade to 4.12.42",
    "is_selected": true,
    "central_stations": []
  }
]
```
