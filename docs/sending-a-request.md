# Sending A Request

## Get a list of supported operations
1. Open `http://<MODULE IP>:8181/` in your browser to see a complete list of supported operations.

## Send Requests

**URL:** `http://<MODULE IP>:8181/remote/json-rpc`

**Body:**

```json
{
    "params": [],
    "jsonrpc": "2.0",
    "method": "<Operation>",
    "id": 1
}
```

