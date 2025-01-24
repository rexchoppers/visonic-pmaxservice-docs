# /panel_info

## Name
/panel_info

## Description
This method returns high level panel configuration information such as settable states, supported features and partitions

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /panel_info`

## Example Response
```json
{
  "serial": "AAAAAA",
  "model": "PowerMaster 10",
  "manufacturer": "Visonic",
  "current_user": "master_user",
  "state_sets": {
    "all": [
      {
        "name": "AWAY",
        "settable": true,
        "options": [
          "NOENTRY",
          "LATCHKEY"
        ],
        "statuses": [
          "EXIT"
        ],
        "transitions": [
          "DISARM",
          "HOME"
        ]
      },
      {
        "name": "HOME",
        "settable": true,
        "options": [
          "NOENTRY"
        ],
        "statuses": [
          "EXIT"
        ],
        "transitions": [
          "DISARM",
          "AWAY"
        ]
      },
      {
        "name": "DISARM",
        "settable": true,
        "options": [],
        "statuses": [],
        "transitions": [
          "DISARM",
          "AWAY",
          "HOME"
        ]
      },
      {
        "name": "ENTRY_DELAY",
        "settable": false,
        "options": [],
        "statuses": [],
        "transitions": [
          "DISARM"
        ]
      },
      {
        "name": "PROGRAMMING",
        "settable": false,
        "options": [],
        "statuses": [],
        "transitions": []
      }
    ]
  },
  "partitions": [
    {
      "id": -1,
      "active": true,
      "exit_delay_time": 30,
      "state_set": "all",
      "name": "ALL"
    }
  ],
  "bypass_mode": "manual_bypass",
  "local_wakeup_needed": false,
  "remote_switch_to_programming_mode_requires_user_acceptance": true,
  "features": {
    "video_on_demand": true,
    "alerts": true,
    "enabling_siren": true,
    "disabling_siren": true,
    "wi_fi_connection": false,
    "set_date_time": true,
    "outputs_setup": true
  }
}
```
