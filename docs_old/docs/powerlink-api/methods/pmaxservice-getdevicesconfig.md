# PmaxService/getDevicesConfig

## Name
PmaxService/getDevicesConfig

## Description
This method returns all device information for the panel. This includes all sensors, keyfobs, etc.

## Parameters
This method does not take any parameters.

## Example Request
```json
{
    "params": [],
    "jsonrpc": "2.0",
    "method": "PmaxService/getDevicesConfig",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": [
        {
            "id": 1,
            "partitions": [
                1
            ],
            "serial": "410-0000",
            "subtype": 1,
            "type": 2
        },
        {
            "id": 1,
            "location": "Front door",
            "partitions": [
                1
            ],
            "serial": "109-0000",
            "subtype": 44,
            "type": 3,
            "zoneSecurityType": 5
        },
        {
            "id": 2,
            "location": "Kitchen",
            "partitions": [
                1
            ],
            "serial": "126-0000",
            "subtype": 12,
            "type": 3,
            "zoneSecurityType": 6
        },
        {
            "id": 3,
            "location": "Utility room",
            "partitions": [
                1
            ],
            "serial": "126-0000",
            "subtype": 12,
            "type": 3,
            "zoneSecurityType": 4
        },
        {
            "id": 4,
            "location": "Living room",
            "partitions": [
                1
            ],
            "serial": "126-0000",
            "subtype": 12,
            "type": 3,
            "zoneSecurityType": 6
        },
        {
            "id": 1,
            "partitions": [
                1
            ],
            "serial": "301-0000",
            "subtype": 2,
            "type": 5
        },
        {
            "id": 2,
            "partitions": [
                1
            ],
            "serial": "301-0000",
            "subtype": 2,
            "type": 5
        }
    ]
}
```