# /configuration

## Name
/configuration

## Description
This method returns the configuration for the specified panel.

## Parameters
- `id` Configuration ID. Use `/configuration_list` to get a list of configurations.

## Authentication
`User-Token` is required.

## Example Request
`GET /configuration?id=100`

## Example Response
Note: Information has been removed as it contains sensitive configuration information

```json
{
  "type": "menu",
  "key": "",
  "name": "",
  "val": [
    ...
  ],
  "version": 503296,
  "timestamp": "2025-01-23T17:41:35+0200",
  "lists": {
    "1": [
      ...
    ]
  }
}
```
