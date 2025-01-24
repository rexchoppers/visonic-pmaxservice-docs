# /panels

## Name
/panels

## Description
This method returns a list of panels that are associated with the user.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /panels`

## Example Response
```json
[
  {
    "panel_serial": "AAAAAA",
    "alias": "Home",
    "role": "MASTER_USER",
    "customization": {
      "id": 1,
      "name": "Default",
      "is_default": true,
      "created": 0,
      "changed": 1689192872,
      "data": {
        "apptype": "",
        "android": "market://details?id=com.visonic.neo",
        "ios": "itms-apps://itunes.apple.com/app/connectalarm/id1300525077",
        "customization": {
          "themes": [
            {
              "name": "Estoril",
              "brightness": "light",
              "colors": {
                "primary": "#006AFF",
                "gradient": [
                  "#00539E",
                  "#21329D",
                  "#2A2A9D"
                ]
              }
            },
            {
              "name": "Azurite",
              "brightness": "dark",
              "colors": {
                "primary": "#00A3FF",
                "gradient": [
                  "#1A2B3B",
                  "#222133",
                  "#261D2D"
                ]
              }
            }
          ]
        }
      }
    }
  }
]
```
