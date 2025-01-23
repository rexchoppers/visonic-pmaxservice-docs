# Visonic API

## Introduction
Visonic/Tyco have their own REST API that are used for the following apps:

- Visonic-Go
- AlarmInstall
- ConnectAlarm

The API points to Visonic/Tyco's PowerManage servers which then passes the request to the alarm panel.

## Details
Endpoint: `https://visonic.tycomonitor.com/rest_api`

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

## Authentication
There are two types of tokens that are passed in the header of the request.

`User-Token`: This token is used for the user to authenticate with the server.

`Session-Token`: Used alongisde the `User-Token`, this token is used for operations on a specific panel.
