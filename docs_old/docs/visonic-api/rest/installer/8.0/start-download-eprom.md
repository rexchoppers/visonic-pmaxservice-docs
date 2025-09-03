# /start_download_eprom

## Name
/start_download_eprom

## Description
This method starts the download of the EPROM from the panel. The download process is asynchronous and the status of the download can be checked using the `/process_status` method.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`POST /start_download_eprom`

```json
{}
```

## Example Response
```json
{
  "process_token": "1814fa15-d9a5-11ef-8676-06640ee4c3d2" // Keep this token to check the status of the download
}
```