# PmaxService/getDeviceStatuses

## Name
PmaxService/getDeviceStatuses

## Description
Returns all status information for a device.

## Parameters
- `params[0]` PowerG Device type ID
- `params[1]` Device ID

## Example Request
```json
{
    "params": [
        3, 3
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getDeviceStatuses",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "id": 3,
        "statuses": {
            "acTrouble": false,
            "alarm": false,
            "bypassZone": false,
            "cleanMeTrouble": false,
            "coldAlert": false,
            "freezerAlert": false,
            "freezingAlert": false,
            "heatAlarmTrouble": false,
            "hotAlert": false,
            "lowBattery": false,
            "maskingTrouble": false,
            "notUpdated": false,
            "oneWayTrouble": false,
            "open": false,
            "smokeAlarm": false,
            "smokeTrouble": false,
            "supervisionTrouble": false,
            "tamperMemory": false,
            "tamperTrouble": false,
            "zoneTrouble": false
        },
        "type": 3
    }
}
```