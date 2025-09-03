# /events

## Name
/events

## Description
This method returns a list of events that have occurred on the panel.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /events`

## Example Response
```json
[
  {
    "event": 198668428,
    "type_id": 993,
    "label": "OFFLINE",
    "description": "BBA module has gone offline",
    "appointment": "IPMP",
    "datetime": "2025-01-13 14:33:27",
    "video": false,
    "device_type": "IPMP",
    "zone": null,
    "zone_name": "",
    "partitions": [
      1
    ]
  },
  {
    "event": 198668429,
    "type_id": 998,
    "label": "OFFLINE",
    "description": "Panel has gone offline",
    "appointment": "IPMP",
    "datetime": "2025-01-13 14:33:27",
    "video": false,
    "device_type": "IPMP",
    "zone": null,
    "zone_name": "",
    "partitions": [
      1
    ]
  },
  {
    "event": 198685335,
    "type_id": 86,
    "label": "ARM",
    "description": "Arm Away",
    "appointment": "Joe Bloggs",
    "datetime": "2025-01-13 16:44:10",
    "video": false,
    "device_type": "USER",
    "zone": 1,
    "zone_name": "Joe Bloggs",
    "partitions": [
      1
    ]
  },
  {
    "event": 199824640,
    "type_id": 27,
    "label": "BURGLER",
    "description": "Control Panel Tamper Restore",
    "appointment": "Control Panel",
    "datetime": "2025-01-21 15:54:48",
    "video": false,
    "device_type": "CONTROL_PANEL",
    "zone": 0,
    "zone_name": "",
    "partitions": [
      1
    ]
  }
]
```
