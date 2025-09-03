# PmaxService/registerClient

## Name
PmaxService/registerClient

## Description
Most methods require the client to be registered first - if not registered, the method will return an error (`The response is invalid: No client registered`).

Identification by the Powerlink module is done by the IP address of the client (i.e. if the request is coming from a registered IP address, the module will accept the request, without any other form of authentication).

Note: only one client can be registered at a time. If a second client tries to register, it will replace the first one.

## Parameters
- `params[0]` IP address of the client
- `params[1]` Unknown parameter (any value seems to work)
- `params[2]` Unknown parameter (perhaps a client name)

## Example Request
```json
{
    "params": [
      "192.168.1.1",
      1234,
      "user"
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/registerClient",
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
