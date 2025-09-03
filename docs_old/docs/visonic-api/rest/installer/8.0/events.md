# /events

## Name
/events

## Description
This method returns a list of events that have occurred on the panel.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /events`

## Example Response
```json
[
  {
    "event": 000000000,
    "type_id": 31,
    "label": "NONE",
    "description": "Cancel Alarm",
    "appointment": "Joe Bloggs",
    "datetime": "2025-01-23 13:09:44",
    "video": false,
    "device_type": "USER",
    "zone": 1,
    "partitions": [
      1
    ],
    "name": "",
    "delivery": {
      "queue": 0,
      "success": 0,
      "failed": 0,
      "retry": 0,
      "processing": 0
    }
  },
  {
    "event": 000000000,
    "type_id": 27,
    "label": "BURGLER",
    "description": "Control Panel Tamper Restore",
    "appointment": "Control Panel",
    "datetime": "2025-01-23 13:24:26",
    "video": false,
    "device_type": "CONTROL_PANEL",
    "zone": 0,
    "partitions": [
      1
    ],
    "name": "",
    "delivery": {
      "queue": 0,
      "success": 0,
      "failed": 0,
      "retry": 0,
      "processing": 0
    }
  }
]
```
