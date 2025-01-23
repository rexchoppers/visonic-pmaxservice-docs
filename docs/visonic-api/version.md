# /version

## Name
/version

## Description
This method returns the different API types and their supported versions

## Parameters
This method does not take any parameters.

## Example Request
GET /version

## Example Response
```json
{
  "rest_versions": [ // Used for User based apps: Visonic Go, ConnectAlarm
    "10.0"
  ],
  "installer_versions": [ // Used for Installed based apps: AlarmInstall
    "8.0"
  ],
  "push_format_versions": [ // ?
    "7"
  ],
  "dls_versions": [ 
    "1.0"
  ]
}
```