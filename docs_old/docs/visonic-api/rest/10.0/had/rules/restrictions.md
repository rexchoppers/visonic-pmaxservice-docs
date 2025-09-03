# /had/rules/restrictions

## Name
/had/rules/restrictions

## Description
Unknown - This method may return request payload validation rules.

## Parameters
This method does not take any parameters.


## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /had/rules/restrictions`

## Example Response
```json
{
  "triggers": [
    {
      "name": "Event",
      "parameters": [
        {
          "name": "event_codes",
          "type": "sEventCodes",
          "value": {
            "vis": {
              "name": "vis",
              "type": "Set<string>",
              "value": null
            },
            "cid": {
              "name": "cid",
              "type": "Set<string>",
              "value": null
            },
            "sia": {
              "name": "sia",
              "type": "Set<string>",
              "value": null
            }
          }
        }
      ]
    },
    {
      "name": "EventProfile",
      "parameters": [
        {
          "name": "profiles",
          "type": "Set<string>",
          "values": [
            "EP_ALL",
            "EP_ALERT",
            "EP_ALARM",
            "EP_RESTORE",
            "EP_OPEN_CLOSE",
            "EP_CAMERA_VIEWED",
            "EP_CAMERA_TROUBLE",
            "EP_HOME_DEVICES_ON_OFF",
            "EP_HOME_DEVICES_TROUBLE",
            "EP_ONLINE",
            "EP_OFFLINE",
            "EP_NOTICE",
            "EP_RRI",
            "EP_ZONE_OPEN_CLOSE",
            "EP_TEMPERATURE",
            "EP_ILLUMINANCE",
            "EP_SYSTEM_PUSH_MSG",
            "EP_DURESS",
            "EP_SYSTEM_EMAIL"
          ]
        }
      ]
    },
    {
      "name": "StateChanged",
      "parameters": [
        {
          "name": "state",
          "type": "string"
        },
        {
          "name": "partition",
          "type": "int"
        }
      ]
    },
    {
      "name": "ZoneChanged",
      "parameters": [
        {
          "name": "zone",
          "type": "int"
        },
        {
          "name": "state",
          "type": "string",
          "values": [
            "Open",
            "Close"
          ]
        }
      ]
    },
    {
      "name": "TemperatureChanged",
      "parameters": [
        {
          "name": "value",
          "type": "int"
        },
        {
          "name": "zone",
          "type": "int"
        },
        {
          "name": "condition",
          "type": "string",
          "values": [
            "MoreThan",
            "MoreOrEqual",
            "LessThan",
            "LessOrEqual",
            "Equal",
            "NotEqual"
          ]
        }
      ]
    },
    {
      "name": "Schedule",
      "parameters": [
        {
          "name": "timezone",
          "type": "string"
        },
        {
          "name": "minutes",
          "type": "Set<int>"
        },
        {
          "name": "hours",
          "type": "Set<int>"
        },
        {
          "name": "days_of_month",
          "type": "Set<int>"
        },
        {
          "name": "months",
          "type": "Set<int>"
        },
        {
          "name": "days_of_week",
          "type": "Set<int>"
        }
      ]
    }
  ],
  "actions": [
    {
      "name": "SetState",
      "parameters": [
        {
          "name": "state",
          "type": "string"
        },
        {
          "name": "options",
          "type": "string[]",
          "values": [
            "NOENTRY",
            "NOEXIT",
            "LATCHKEY"
          ]
        },
        {
          "name": "partition",
          "type": "int"
        }
      ]
    },
    {
      "name": "OperateOutput",
      "parameters": [
        {
          "name": "output",
          "type": "int"
        },
        {
          "name": "demand_state",
          "type": "string",
          "values": [
            "On",
            "Off"
          ]
        }
      ]
    },
    {
      "name": "SendEmail",
      "parameters": [
        {
          "name": "body",
          "type": "string"
        }
      ]
    },
    {
      "name": "SendPushNotification",
      "parameters": [
        {
          "name": "message",
          "type": "string"
        }
      ]
    }
  ]
}
```
