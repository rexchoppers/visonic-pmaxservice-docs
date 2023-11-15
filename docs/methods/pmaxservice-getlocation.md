# PmaxService/getLocation

## Name
PmaxService/getLocation

## Description
This method returns information for a zone location.

## Parameters
- `params[0]` Location ID

## Example Request
```json
{
    "params": [
        1
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getLocation",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "id": 1,
        "value": "Loft"
    }
}
```