# Powerlink API

## Introduction
The Powerlink module which is used to interact between the panel and Powermanage server has its own JSON RPC API.

## Get a list of supported operations
1. Open `http://<MODULE IP>:8181/` in your browser to see a complete list of supported operations.

## Send Requests

**URL:** `http://<MODULE IP>:8181/remote/json-rpc`

**Method:**: `POST`

**Body:**

```json
{
    "params": <Method.Parameters>,
    "jsonrpc": "2.0",
    "method": <Method.Name>,
    "id": 1
}
```

- A list of supported methods and their parameters can be found under the **Methods** section
- Parameter order does matter so make sure to check the order of the parameters in the parameters section
- For some methods, the client needs to be registered first, see the [PmaxService/registerClient](./methods/pmaxservice-registerclient.md) method for more details
