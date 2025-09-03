# /feature_set

## Name
/feature_set

## Description
This method returns all supported features for the panel.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /feature_set`

## Example Response
```json
{
  "events": {
    "is_enabled": true
  },
  "datetime": {
    "is_enabled": true
  },
  "partitions": {
    "is_enabled": false,
    "is_labels_enabled": false,
    "is_labels_editable": true,
    "max_partitions": 3
  },
  "sirens": {
    "can_enable": true,
    "can_disable": true
  },
  "devices": {
    "is_enabled": true,
    "is_enrollable": true,
    "devices": [
      {
        "enrollment_prefix": "300",
        "name": "BASIC_KEYFOB",
        "enroll": true,
        "removing": true,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "301",
        "name": "KEYFOB_ARM_LED",
        "enroll": true,
        "removing": true,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "305",
        "name": "DSC_KEYFOB_1",
        "enroll": true,
        "removing": true,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "306",
        "name": "DSC_KEYFOB_2",
        "enroll": true,
        "removing": true,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "073",
        "name": "PGM_ON_ZONE",
        "enroll": true,
        "removing": true,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "070",
        "name": "PGM_ON_PANEL",
        "enroll": true,
        "removing": true,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "",
        "name": "VISONIC_PANEL",
        "enroll": false,
        "removing": false,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "120",
        "name": "MOTION",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "122",
        "name": "CURTAIN",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "140",
        "name": "MOTION_CAMERA",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "160",
        "name": "GLASS_BREAK",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "123",
        "name": "MOTION_V_ANTIMASK",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "150",
        "name": "MOTION_DUAL",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "130",
        "name": "MOTION_OUTDOOR",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "142",
        "name": "MOTION_OUTDOOR_CAMERA",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "161",
        "name": "GLASS_BREAK_SMART",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "126",
        "name": "FLAT_PIR_SMART",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "127",
        "name": "S_CEILING_SR",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "128",
        "name": "S_CEILING_LR",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "129",
        "name": "S_OUT_CURTAIN",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "200",
        "name": "SMOKE",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "201",
        "name": "SMOKE_HEAT",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "230",
        "name": "GAS",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "220",
        "name": "CO",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "240",
        "name": "FLOOD",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "250",
        "name": "TEMPERATURE",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "241",
        "name": "FLOOD_PROBE",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "221",
        "name": "S_CO_SENSOR",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "202",
        "name": "S_SMOKE_AND_HEAT",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "100",
        "name": "CONTACT",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "101",
        "name": "CONTACT_AUX",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "109",
        "name": "MC303_VANISH",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "104",
        "name": "CONTACT_V",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "105",
        "name": "CONTACT_IOS",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "106",
        "name": "CONTACT_4_IN",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "107",
        "name": "S_OUT_MC_1IN",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "171",
        "name": "SHOCK_AUX",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "172",
        "name": "SHOCK_CONTACT_G3",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "170",
        "name": "SHOCK_CONTACT_AUX_ANTIMASK",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "173",
        "name": "SHOCK_CONTACT_G2",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "053",
        "name": "HW_ZONE_CONNECTED_TO_WL_EXPANDER_IOV",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "050",
        "name": "HW_ZONE_CONNECTED_DIRECTLY_TO_THE_PANEL",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": true
      },
      {
        "enrollment_prefix": "370",
        "name": "KEYPAD",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "371",
        "name": "PROXIMITY_KEYPAD",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "374",
        "name": "LCD_KEYPAD",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "375",
        "name": "LCD_PRG_KEYPAD",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "410",
        "name": "OUTDOOR",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "400",
        "name": "INDOOR",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "411",
        "name": "AC_OUTDOOR",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "",
        "name": "POWER_LINK",
        "enroll": false,
        "removing": false,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "",
        "name": "GENERIC_PROXY_TAG",
        "enroll": false,
        "removing": false,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "320",
        "name": "SINGLE_BUTTON",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "322",
        "name": "TWO_BUTTON",
        "enroll": false,
        "removing": false,
        "partitions_required": true,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "430",
        "name": "BASIC_REPEATER",
        "enroll": false,
        "removing": false,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      },
      {
        "enrollment_prefix": "",
        "name": "GENERIC_PGM",
        "enroll": false,
        "removing": false,
        "partitions_required": false,
        "users_required": false,
        "is_zone_type_applicable": false
      }
    ],
    "zone_types": [
      "NON_ALARM",
      "EMERGENCY",
      "FLOOD",
      "GAS",
      "DELAY_1",
      "DELAY_2",
      "INTERIOR_FOLLOW",
      "PERIMETER",
      "PERIMETER_FOLLOW",
      "H24_SILENT",
      "H24_AUDIBLE",
      "FIRE",
      "INTERIOR",
      "HOME_DELAY",
      "TEMPERATURE",
      "ARMING_KEY",
      "GUARD_KEYBOX",
      "OUTDOOR",
      "INTERIOR_DELAY",
      "TAMPER",
      "LINE_FAIL",
      "PSU_FAIL",
      "PANIC",
      "CUSTOM_1",
      "CUSTOM_2"
    ],
    "video_on_demand": true
  },
  "home_automation_devices": {
    "is_enabled": true,
    "enabling": true,
    "disabling": true,
    "toggling": true,
    "setting": true
  },
  "state": {
    "is_enabled": true,
    "can_set": true,
    "can_get": true
  },
  "faults": {
    "is_enabled": true,
    "has_alarms": true,
    "has_alerts": true,
    "has_troubles": true
  },
  "diagnostic": {
    "is_enabled": false
  },
  "wifi": {
    "is_enabled": false
  },
  "locations": {
    "is_enabled": true
  },
  "user": {
    "editable_features": [
      "UEF_CODE",
      "UEF_ROLE",
      "UEF_PARTITIONS",
      "UEF_LABEL",
      "UEF_CREATE_USER",
      "UEF_REMOVE_USER"
    ],
    "code_length": [
      4
    ]
  },
  "emergency": {
    "is_enabled": true,
    "is_support_specified_partitions": true
  }
}
```
