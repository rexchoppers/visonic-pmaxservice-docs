# PmaxService/getPanelStatuses

## Name
PmaxService/getPanelStatuses

## Description
This method returns information on partitions and the panel's current status

## Parameters
This method does not take any parameters.

## Example Request
```json
{
    "params": [],
    "jsonrpc": "2.0",
    "method": "PmaxService/getPanelStatuses",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "datetime": "20231107225917",
        "partitions": [
            {
                "partition": 1,
                "state": "DISARM",
                "statuses": {
                    "activeBit": true,
                    "alertBit": false,
                    "bypassBit": false,
                    "fireBit": false,
                    "instantBit": false,
                    "latchkeyBit": false,
                    "memoryBit": false,
                    "needEngResetBit": false,
                    "readyBit": true,
                    "troubleBit": false
                }
            }
        ],
        "statuses": {
            "acTrouble": false,
            "communicationFailure": false,
            "enrollingModeBit": false,
            "fuseTrouble": false,
            "jammingTrouble": false,
            "lineFailure": false,
            "lowBattery": false,
            "noActive": false,
            "tamperMemory": false,
            "tamperTrouble": false
        }
    }
}
```