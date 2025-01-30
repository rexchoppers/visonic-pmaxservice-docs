# PmaxService/enableSsh

## Name
PmaxService/enableSsh

## Description
This method enables SSH access to the module

## Parameters
- `params[0]` Your user code/installer code
- `params[1]` Enable SSH access

## Example Request
```json
{
    "params": [
      "1234",
      true
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/enableSsh",
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