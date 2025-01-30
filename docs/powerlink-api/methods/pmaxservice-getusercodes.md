# PmaxService/getUserCodes

## Name
PmaxService/getUserCodes

## Description
This method returns all the user codes for the panel

## Parameters
- `params[0]` Your user code you use to arm + disarm the panel

## Example Request
```json
{
    "params": [
        "1234"
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getUserCodes",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": [
        {
            "partitions": [
                1,
                2,
                3
            ],
            "userCode": "1234",
            "userId": 1
        }
    ]
}
```