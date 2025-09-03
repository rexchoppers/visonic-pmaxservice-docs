# /auth

## Name
/auth

## Description
This method is used to authenticate the user with installer REST API. The user will receive a `User-Token` which is used for all subsequent requests.

## Parameters
- `email` Email
- `password` Password
- `device_id` App ID
- `device_info` Device info

## Authentication
This method does not require authentication.

## Example Request
`POST /auth`

```json
{
  "email": "<email>>",
  "password": "<password>",
  "device_id": "<device id>",
  "device_info": "IN2013" // Device model?
}
```

## Example Response
```json
{
  "user_token": "2TBJomfS9M21Ubn07TNu222vTu5H9y12", // This will be used for all subsequent requests where `User-Token` is required
  "info": {
    "name": "Connor",
    "email": "<Email>",
    "phone": "44777777777"
  },
  "server": {
    "installer_allowed_to_remove_panels": true,
    "virtual_panel_support": false
  },
  "license": {
    "name": "Enterprise",
    "hmac": "RandomHMACLicense",
    "valid": {
      "not_after": "2030-08-27T00:00:00+00:00",
      "not_before": "2024-09-22T00:00:00+00:00"
    },
    "features": [
      {
        "allowed": true,
        "description": "",
        "feature": "interactive"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "interactive/end_user_reporting"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "interactive/installer_app"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "interactive/user_app"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "receiver"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "receiver/central_stations"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "receiver/receive_events"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/dls_api"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/panel_configuration"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/panel_diagnostic"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/panel_event_log"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/panel_labels"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/panel_set_state"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/remote_inspection"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/reports"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/software_upgrade"
      },
      {
        "allowed": true,
        "description": "",
        "feature": "resolve/virtual_keypad"
      }
    ],
    "limits": [
      {
        "description": "Automation Software connections",
        "limit": "central_station_num",
        "value": 100
      },
      {
        "description": "PowerMaster/Max Systems",
        "limit": "panels",
        "value": 100000
      },
      {
        "description": "PowerSeries Dual path Systems",
        "limit": "panels_dual_path",
        "value": 10000
      },
      {
        "description": "PowerSeries NEO/PRO Systems",
        "limit": "panels_neo",
        "value": 100000
      }
    ]
  }
}
```