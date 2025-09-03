# /panel/login

## Name
/panel/login

## Description
This method is used to login and generate a session with a panel.

## Parameters
- `email` Email
- `password` Password
- `app_id` App ID

## Authentication
`User-Token` is required.

## Example Request
`POST /panel/login`

```json
{
  "panel_serial": "AAAAAA",
  "user_code": "1111",
  "app_id": "2d513ccb-f3ec-4656-b506-f158b6689b1e", // See App IDs
  "app_type": "com.visonic.powermaxapp" // See App IDs
}
```

## Example Response
```json
{
  "session_token": "c79205bc-6168-47eb-aaa9-b430e4cfd456" // This will be used for all subsequent panel requests where `Session-Token` is required
}
```