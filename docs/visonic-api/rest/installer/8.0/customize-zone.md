# /customize_zone

## Name
/customize_zone

## Description
This method updates zone information

## Parameters
- `hel_id` Zone ID
- `name` Zone name

## Authentication
`User-Token` is required.

## Example Request
`POST /customize_zone`

```json
{
  "hel_id": 5,
  "name": "Child room"
}
```

## Example Response
```json
{
  "process_token": "1814fa15-d9a5-11ef-8676-06640ee4c3d2" // Keep this token to check the status of the download
}
```