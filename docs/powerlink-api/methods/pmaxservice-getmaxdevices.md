# PmaxService/getMaxDevices

## Name
PmaxService/getMaxDevices

## Description
This method returns the maximum number of devices per type that can be added to the system.

## Parameters
This method does not take any parameters.

## Example Request
```json
{
    "params": [
        
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getMaxDevices",
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
            "max": 4,
            "type": 0
        },
        {
            "max": 15,
            "type": 1
        },
        {
            "max": 4,
            "type": 2
        },
        {
            "max": 30,
            "type": 3
        },
        {
            "max": 8,
            "type": 4
        },
        {
            "max": 8,
            "type": 5
        }
    ]
}
```