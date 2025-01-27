# /home_automation_devices

## Name
/home_automation_devices

## Description
This method returns a list of home automation devices that are connected to the panel.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /home_automation_devices`

## Example Response
```json
[
  {
    "id": 1,
    "class": "pgm",
    "name": null,
    "user_type": null,
    "device_type": "PGM",
    "product_type": null,
    "product_name": null,
    "state": {
      "pgm": "off"
    },
    "location": {
      "id": 12,
      "name": "Front door"
    },
    "partitions": [
      -1
    ],
    "supported_commands": [
      "output"
    ],
    "has_timer": true,
    "label_editable": true
  }
]
```
