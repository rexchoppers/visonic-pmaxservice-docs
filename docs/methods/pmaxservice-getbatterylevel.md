# PmaxService/getBatteryLevel

## Name
PmaxService/getBatteryLevel

## Description
This method returns the battery level of the panel.

## Parameters
This method does not take any parameters.

## Example Request
```json
{
    "params": [],
    "jsonrpc": "2.0",
    "method": "PmaxService/getBatteryLevel",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": 100
}
```
- `result` - The battery level of the panel in percent.