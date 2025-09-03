# /panel_access_info

## Name
/panel_access_info

## Description
This method returns access information for the specified panel.

## Parameters
- `panel_web_name` Panel serial number
- `app_type` App ID (See App IDs)

## Authentication
`User-Token` is required.

## Example Request
`GET /panel_access_info?panel_web_name=AAAAAA&app_type=696a5dd8-1ace-4667-b3f4-fc4bd295e597`

## Example Response
```json
{
  "user": {
    "status": "active",
    "error": null,
    "stage": null
  },
  "installer": {
    "status": "active",
    "error": null,
    "stage": null
  }
}
```
