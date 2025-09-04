# Visonic API

## Introduction
Visonic/Tyco have their own REST API that are used for the following apps:

- Visonic-Go
- AlarmInstall
- ConnectAlarm

The API points to Visonic/Tyco's PowerManage servers which then passes the request to the alarm panel.

## Details
Normal user endpoint: `https://visonic.tycomonitor.com/rest_api/{rest_version}`

Installer endpoint: `https://visonic.tycomonitor.com/rest_api/installer/{installer_version}`


## Versions
There are several versions and types of this API available. Calling the `/version` endpoint will return a list of supported versions for each type of API.

```json
{
  "rest_versions": [
    "10.0"
  ],
  "installer_versions": [
    "8.0"
  ],
  "push_format_versions": [
    "7"
  ],
  "dls_versions": [
    "1.0"
  ]
}
```