# /panel_info

## Name
/panel_info

## Description
This method returns high level panel configuration information such as current state, partitions and firmware information.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /panel_info`

## Example Response
```json
{
  "name": "AAAAAA",
  "serial": "AAAAAA",
  "model": "PowerMaster 10",
  "manufacturer": "Visonic",
  "current_user": "INSTALLER",
  "bypass_mode": "manual_bypass",
  "local_wakeup_needed": false,
  "remote_switch_to_programming_mode_requires_user_acceptance": false,
  "state_sets": {
    "default": null,
    "all": [
      {
        "name": "PROGRAMMING",
        "settable": false,
        "options": null,
        "statuses": null,
        "transitions": null
      }
    ]
  },
  "partitions": [
    {
      "id": -1,
      "name": "ALL",
      "active": true,
      "exit_delay": 30,
      "state_set": "all"
    }
  ],
  "firmware": {
    "panel_boot_version": "JS702413 I01.033",
    "panel_default_version": "J-703883 I20.214",
    "panel_eeprom_version": "7.174",
    "panel_hw_version": "PowerMaster-10",
    "panel_rsu_version": "JS702414 I02.036",
    "panel_sw_last_upgraded": "",
    "panel_sw_version": "JS703642 I20.214",
    "powerlink_configuration_variant": "adtuk",
    "powerlink_hw_version": "plink3",
    "powerlink_sw_last_upgraded": "",
    "powerlink_sw_version": "7.5.58"
  },
  "features": {
    "video_on_demand": true,
    "alerts": true,
    "enabling_siren": true,
    "disabling_siren": true,
    "wi_fi_connection": false,
    "set_date_time": true,
    "outputs_setup": true,
    "gsm_rssi_level_on_request": false
  }
}
```
