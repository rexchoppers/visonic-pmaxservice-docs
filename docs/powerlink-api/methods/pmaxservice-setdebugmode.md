# PmaxService/setPanelState

## Name
PmaxService/setDebugMode

## Description
Enables or disables the debug mode of the panel. Note: This is not supported on my panel.

## Parameters
- `params[0]` Your installer code
- `params[1]` Debug mode true/false


## Example Request
```json
{
    "params": [
      1234,
      true
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/setDebugMode",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "status": "success"
    }
}
```