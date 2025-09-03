# /initiate_rri

## Name
/initiate_rri

## Description
This method initiates a remote inspection.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`POST /initiate_rri`

```json
{}
```

## Example Response
```json
{
  "process_token": "1814fa15-d9a5-11ef-8676-06640ee4c3d2" // Keep this token to check the status of the download
}
```