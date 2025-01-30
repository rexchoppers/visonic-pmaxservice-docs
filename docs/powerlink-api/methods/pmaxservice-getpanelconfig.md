# PmaxService/getPanelConfig

## Name
PmaxService/getPanelConfig

## Description
This method returns all configuration information for the panel.

## Parameters
This method does not take any parameters.

## Example Request
```json
{
    "params": [
      
    ],
    "jsonrpc": "2.0",
    "method": "PmaxService/getPanelConfig",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "abortTime": 1,
        "bypassArmMode": "MANUAL_BYPASS",
        "duressCode": "0000",
        "eepromVersion": {
            "eeprom_model": 7,
            "eeprom_sub_model": 174
        },
        "entryDelay1": 30,
        "entryDelay2": 60,
        "exitDelay": 30,
        "gprsEnrolled": false,
        "kidsComeHomeEnabled": false,
        "latchkeyEnabled": true,
        "panelId": "0AAA0A",
        "partitionEnabled": false,
        "plinkVariant": "adtuk",
        "plinkVersion": "7.5.58",
        "pmaxDefaultVersion": "J-703883 I20.214",
        "pmaxVersion": "JS703642 I20.214",
        "quickArmEnabled": false,
        "viewOnDemand": "VIEW_IN_ALL_MODES",
        "viewOnDemandTimeWindow": "ALWAYS"
    }
}
```