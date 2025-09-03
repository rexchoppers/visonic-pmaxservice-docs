# PmaxService/getUserCode

## Name
PmaxService/getUserCode

## Description
This method returns all the user codes for a particular user.

## Parameters
- `params[0]` Your user code you use to arm + disarm the panel
- `params[1]` The user ID you want to get the codes for

## Example Request
```json
{
    "params": [
        "1234",
        1
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getUserCode",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "partitions": [
            1,
            2,
            3
        ],
        "userCode": "1234",
        "userId": 1
    }
}
```