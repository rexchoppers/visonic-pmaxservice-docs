# /panel/login

## Name
/panel/login

## Description
This method is used to login and generate an installer session with a panel.

## Parameters
- `panel_serial` Panel Serial Number
- `installer_code` Installer Code
- `app_id` App ID
- `app_type` App Type

## Authentication
`User-Token` is required.

## Example Request
`POST /panel/login`

```json
{
  "panel_serial": "AAAAAA",
  "installer_code": "9999",
  "app_id": "9e739e1d-2f3e-42ad-8f71-7563ada7ea13",
  "app_type": "com.visonic.configurator.alarm_in"
}
```

## Example Response
```json
{
  "session_token": "c79205bc-6168-47eb-aaa9-b430e4cfd456" // This will be used for all subsequent panel requests where `Session-Token` is required
}
```