# /auth

## Name
/auth

## Description
This method is used to authenticate the user with REST API. The user will receive a `User-Token` which is used for all subsequent requests.

## Parameters
- `params[0]` Email
- `params[1]` Password
- `params[2]` App ID

## Example Request
POST /apptype

```json
{
  "email": "<email>",
  "password": "<password>",
  "app_id": "<app id>"
}
```

## Example Response
```json
{
  "user_token": "917678b6-db1f-49b9-8c1d-cb9c1a4d4a2f", // This will be used for all subsequent requests
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
```

## App IDs
- 2d513ccb-f3ec-4656-b506-f158b6689b1e: Visonic Go