# /walk_test_status

## Name
/walk_test_status

## Description
This method returns the informations of the last walk test.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /walk_test_status`

## Example Response
```json
[
  {
    "zone": 1,
    "device_type": "ZONE",
    "status": "failed"
  },
  {
    "zone": 2,
    "device_type": "ZONE",
    "status": "passed"
  },
  {
    "zone": 3,
    "device_type": "ZONE",
    "status": "failed"
  },
  {
    "zone": 4,
    "device_type": "ZONE",
    "status": "failed"
  },
  {
    "zone": 1,
    "device_type": "KEYFOB",
    "status": "failed"
  },
  {
    "zone": 2,
    "device_type": "KEYFOB",
    "status": "failed"
  },
  {
    "zone": 1,
    "device_type": "WIRELESS_COMMANDER",
    "status": "failed"
  },
  {
    "zone": 5,
    "device_type": "ZONE",
    "status": "failed"
  },
  {
    "zone": 6,
    "device_type": "ZONE",
    "status": "failed"
  },
  {
    "zone": 7,
    "device_type": "ZONE",
    "status": "failed"
  },
  {
    "zone": 8,
    "device_type": "ZONE",
    "status": "failed"
  }
]
```
