# PmaxService/setPanelState

## Name
PmaxService/setPanelState

## Description
Sets the state of the panel. For example, if you're looking to arm/disarm your panel, you would use this method

## Parameters
- `params[0]` Your user code you use to arm + disarm the panel
- `params[1]` The state you want to set your panel - `AWAY`, `HOME`, `DISARM` 
- `params[2]` The partition you want to set the state of (Requires clarification)
- `params[3]` Unknown (Requires clarification)
- `params[4]` Unknown (Requires clarification)

## Example Request
```json
{
    "params": [
      1234,
      "HOME",
      1,
      true,
      true
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/setPanelState",
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