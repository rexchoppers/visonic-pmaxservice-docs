# /panel/add

## Name
/panel/add

## Description
This method is used to add a new panel to the installer account.

## Parameters
- `alias` Panel name
- `panel_serial` Panel Serial
- `installer_code` Installer Code

## Authentication
`User-Token` is required.

## Example Request
`POST /panel/add`

```json
{
  "alias": "Test",
  "panel_serial": "AAAAAA",
  "installer_code": "9999"
}
```

## Example Response
Unsure of response at this this

```json
{}
```