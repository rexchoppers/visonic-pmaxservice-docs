# /apptype

## Name
/apptype

## Description
This endpoint appears to return links to the App/Google Play Store for the ConnectAlarm app.

## Parameters
This method does not take any parameters.

## Authentication
This method does not require authentication.

## Example Request
GET /apptype

## Example Response
```json
{
  "apptype": "",
  "android": "market://details?id=com.visonic.neo",
  "ios": "itms-apps://itunes.apple.com/app/connectalarm/id1300525077"
}
```