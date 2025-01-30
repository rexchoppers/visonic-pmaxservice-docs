# PmaxService/getEepromVersion

## Name
PmaxService/getEepromVersion

## Description
This method returns the EEPROM version of the panel.

## Parameters
This method does not take any parameters.

## Example Request
```json
{
    "params": [],
    "jsonrpc": "2.0",
    "method": "PmaxService/getEepromVersion",
    "id": 1
}
```

## Example Response
```json
{
    "id": 1,
    "jsonrpc": "2.0",
    "result": {
        "eeprom_model": 7,
        "eeprom_sub_model": 174
    }
}
```