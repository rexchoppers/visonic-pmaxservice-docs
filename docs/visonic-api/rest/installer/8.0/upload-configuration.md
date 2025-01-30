# /upload_configuration

## Name
/upload_configuration

## Description
This method uploads a configuration update to the panel. Please be careful when using this method as it is untested and may cause issues with the panel.

## Parameters
- `diff` Configuration difference to upload
- `version` Unknown parameter

## Authentication
`User-Token` is required.

## Example Request
`POST /upload_configuration`

```json
{
  "diff": [
    [
      "EE_ACCOUNT_TEL1",
      "006666"
    ]
  ],
  "version": 503296
}
```

## Example Response
```json
{
  "process_token": "1814fa15-d9a5-11ef-8676-06640ee4c3d2" // Keep this token to check the status of the download
}
```