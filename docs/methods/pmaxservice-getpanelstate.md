# PmaxService/getPanelState

## Name
PmaxService/getPanelState

## Description
This method returns information on the panel's state for a particular partition

## Parameters
- `params[0]` Partition ID

## Example Request
```json
{
    "params": [
        1
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getPanelState",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "partition": 1,
        "state": "DISARM"
    }
}
```