# /process_status

## Name
/process_status

## Description
This method returns the status of the specified process.

## Parameters
- `process_token` Process token

## Authentication
`User-Token` is required.

## Example Request
`GET /process_status?process_token=b4255ac8-8086-48b1-976a-61e0a584cfa3`

## Example Response
```json
[
  {
    "token": "b4255ac8-8086-48b1-976a-61e0a584cfa3",
    "status": "handled",
    "message": "",
    "error": null
  }
]
```
