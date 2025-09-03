# /start_download_device_configuration

## Name
/start_download_device_configuration

## Description
This method starts the download of the configuration for a specific device. The download process is asynchronous and the status of the download can be checked using the `/process_status` method.

## Parameters
- `panel_serial` Panel serial number
- `device_type` Device type
- `zone` Zone number ?

## Authentication
`User-Token` is required.

## Example Request
`POST /start_download_device_configuration`

```json
{
  "panel_serial": "AAAAAA",
  "device_type": "POWER_LINK",
  "zone": 1
}
```

## Example Response
```json
{
  "process_token": "1814fa15-d9a5-11ef-8676-06640ee4c3d2" // Keep this token to check the status of the download
}
```