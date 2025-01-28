# /status

## Name
/status

## Description
This method returns basic panel information such as BBA connected status, partition status, and panel status.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /status`

## Example Response
```json
{
  "connected": false,
  "connected_status": {
    "bba": {
      "is_connected": false,
      "state": "online"
    }
  },
  "discovery": {
    "completed": true,
    "stages": 11,
    "in_queue": 0,
    "triggered": null
  },
  "partitions": [
    {
      "id": -1,
      "state": "DISARM",
      "status": "",
      "ready": true,
      "options": []
    }
  ],
  "rssi": {
    "level": "",
    "network": ""
  }
}
```
