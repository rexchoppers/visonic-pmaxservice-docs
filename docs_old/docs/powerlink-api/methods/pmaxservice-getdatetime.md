# PmaxService/getDateTime

## Name
PmaxService/getDateTime

## Description
This method returns the panel's current date AND time

## Parameters
This method does not take any parameters.

## Example Request
```json
{
    "params": [],
    "jsonrpc": "2.0",
    "method": "PmaxService/getDateTime",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": "20231107224814"
}
```
- `result` - The current date and time in the format `YYYYMMDDHHMMSS`