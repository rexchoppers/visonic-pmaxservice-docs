# /panel/diagnostics

## Name
/panel/diagnostics

## Description
This method is used to get diagnostic information about the specified panel.

## Parameters
- `panel_serial` Panel serial number

## Authentication
`User-Token` is required.

## Example Request
`POST /panel/diagnostics`

```json
{
  "panel_serial": "AAAAAA"
}
```

## Example Response
```json
{
  "connection": {
    "installed": [
      "CHANNEL_BBA"
    ],
    "status": {
      "P1P2": [
        {
          "number": 1,
          "channel_type": "CHANNEL_BBA",
          "value": "CONNECTED",
          "encryption": "ENCRYPTED"
        },
        {
          "number": 2,
          "channel_type": "CHANNEL_BBA",
          "value": "CONFIGURED_OUTSIDE_PM"
        },
        {
          "number": 1,
          "channel_type": "CHANNEL_GPRS",
          "value": "NOT_CONFIGURED"
        },
        {
          "number": 2,
          "channel_type": "CHANNEL_GPRS",
          "value": "NOT_CONFIGURED"
        }
      ],
      "PNET": [
        {
          "number": 1,
          "channel_type": "CHANNEL_BBA",
          "value": "ONLINE",
          "encryption": "ENCRYPTED"
        },
        {
          "number": 2,
          "channel_type": "CHANNEL_BBA",
          "value": "CONFIGURED_OUTSIDE_PM"
        }
      ]
    }
  },
  "troubles": []
}
```