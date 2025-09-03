# PmaxService/getMaxDevice

## Name
PmaxService/getMaxDevice

## Description
This method returns the maximum number of devices for a particular device type that can be added to the system.

## Parameters
- `params[0]` PowerG Device type ID

## Example Request
```json
{
    "params": [
        3
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getMaxDevice",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "max": 30,
        "type": 3
    }
}
```