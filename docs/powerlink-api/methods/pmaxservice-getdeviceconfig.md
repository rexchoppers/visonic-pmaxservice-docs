# PmaxService/getDeviceConfig

## Name
PmaxService/getDeviceConfig

## Description
Returns all configuration information for a device.

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
    "method": "PmaxService/getDeviceConfig",
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
        "location": "Utility room",
        "partitions": [
            1
        ],
        "serial": "000-0001",
        "subtype": 12,
        "type": 3,
        "zoneSecurityType": 4
    }
}
```