# /status

## Name
/status

## Description
This method returns basic panel information such as BBA connected status and partition status.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /status`

## Example Response
```json
{
  "bba": {
    "connected": true,
    "state": "online"
  },
  "gprs": null,
  "wifi": null,
  "bba_over_gprs": null,
  "usb": null,
  "last_discovery": "0001-01-01T00:00:00Z",
  "partitions": [
    {
      "id": -1,
      "state": "DISARM",
      "status": "",
      "options": [],
      "ready": true
    }
  ]
}
```
