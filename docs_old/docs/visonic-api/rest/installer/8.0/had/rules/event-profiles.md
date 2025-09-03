# /had/rules/event-profiles/{locale}

## Name
/had/rules/event-profiles/{locale}

## Description
This method returns the events, translations, and SIA codes for the specified locale.

## Parameters
- `locale` - The locale to return the event profiles for. This is a required parameter.

## Authentication
`User-Token` is required.

## Example Request
`GET /had/rules/event-profiles/en_US`

## Example Response
```json
[
  {
    "profile": {
      "id": "EP_ALERT",
      "description": "Alert",
      "description_original": "Alert"
    },
    "events": [
      {
        "description": "Communication Loss",
        "description_original": "Communication Loss",
        "description_placeholder_arguments": [],
        "code_vis": "10",
        "code_cid": "1383",
        "code_sia": "NTA",
        "type_id": 12,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "General Trouble",
        "description_original": "General Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "15",
        "code_cid": "1412",
        "code_sia": "NRS",
        "type_id": 17,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "System Inactive",
        "description_original": "System Inactive",
        "description_placeholder_arguments": [],
        "code_vis": "30",
        "code_cid": "1654",
        "code_sia": "NNA",
        "type_id": 34,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "No Active",
        "description_original": "No Active",
        "description_placeholder_arguments": [],
        "code_vis": "34",
        "code_cid": "1641",
        "code_sia": "NNA",
        "type_id": 38,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Supervision (Inactive)",
        "description_original": "Supervision (Inactive)",
        "description_placeholder_arguments": [],
        "code_vis": "39",
        "code_cid": "1381",
        "code_sia": "NBZ",
        "type_id": 43,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Low Battery",
        "description_original": "Low Battery",
        "description_placeholder_arguments": [],
        "code_vis": "41",
        "code_cid": "1384",
        "code_sia": "NXT",
        "type_id": 45,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "AC Fail",
        "description_original": "AC Fail",
        "description_placeholder_arguments": [],
        "code_vis": "43",
        "code_cid": "1301",
        "code_sia": "NAT",
        "type_id": 47,
        "label": "EL_AC_FAIL",
        "label_description": "EL_AC_FAIL"
      },
      {
        "description": "Control Panel Low Battery",
        "description_original": "Control Panel Low Battery",
        "description_placeholder_arguments": [],
        "code_vis": "45",
        "code_cid": "1302",
        "code_sia": "NYT",
        "type_id": 49,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "RF Jamming",
        "description_original": "RF Jamming",
        "description_placeholder_arguments": [],
        "code_vis": "47",
        "code_cid": "1344",
        "code_sia": "NBT",
        "type_id": 51,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Communications Failure",
        "description_original": "Communications Failure",
        "description_placeholder_arguments": [],
        "code_vis": "49",
        "code_cid": "1350",
        "code_sia": "NLT",
        "type_id": 53,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Telephone Line Failure",
        "description_original": "Telephone Line Failure",
        "description_placeholder_arguments": [],
        "code_vis": "51",
        "code_cid": "1351",
        "code_sia": "NLT",
        "type_id": 55,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Fuse Failure",
        "description_original": "Fuse Failure",
        "description_placeholder_arguments": [],
        "code_vis": "54",
        "code_cid": "1321",
        "code_sia": "NYA",
        "type_id": 58,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Keyfob Low Battery",
        "description_original": "Keyfob Low Battery",
        "description_placeholder_arguments": [],
        "code_vis": "56",
        "code_cid": "1384",
        "code_sia": "NXT",
        "type_id": 60,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Battery Disconnect",
        "description_original": "Battery Disconnect",
        "description_placeholder_arguments": [],
        "code_vis": "59",
        "code_cid": "1311",
        "code_sia": "NYM",
        "type_id": 63,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Remote Commander Low Battery",
        "description_original": "Remote Commander Low Battery",
        "description_placeholder_arguments": [],
        "code_vis": "60",
        "code_cid": "1384",
        "code_sia": "NXT",
        "type_id": 64,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Remote Commander Inactive",
        "description_original": "Remote Commander Inactive",
        "description_placeholder_arguments": [],
        "code_vis": "62",
        "code_cid": "1381",
        "code_sia": "NBZ",
        "type_id": 66,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Low Battery Acknowledge",
        "description_original": "Low Battery Acknowledge",
        "description_placeholder_arguments": [],
        "code_vis": "64",
        "code_cid": "1319",
        "code_sia": "000",
        "type_id": 68,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Clean Me",
        "description_original": "Clean Me",
        "description_placeholder_arguments": [],
        "code_vis": "65",
        "code_cid": "000",
        "code_sia": "000",
        "type_id": 69,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Fire Trouble",
        "description_original": "Fire Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "66",
        "code_cid": "1373",
        "code_sia": "NFT",
        "type_id": 70,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Low Battery",
        "description_original": "Low Battery",
        "description_placeholder_arguments": [],
        "code_vis": "67",
        "code_cid": "1384",
        "code_sia": "NXT",
        "type_id": 71,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "AC Fail",
        "description_original": "AC Fail",
        "description_placeholder_arguments": [],
        "code_vis": "69",
        "code_cid": "1301",
        "code_sia": "NAT",
        "type_id": 73,
        "label": "EL_AC_FAIL",
        "label_description": "EL_AC_FAIL"
      },
      {
        "description": "Supervision (Inactive)",
        "description_original": "Supervision (Inactive)",
        "description_placeholder_arguments": [],
        "code_vis": "71",
        "code_cid": "1381",
        "code_sia": "NBZ",
        "type_id": 75,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Gas Alert",
        "description_original": "Gas Alert",
        "description_placeholder_arguments": [],
        "code_vis": "73",
        "code_cid": "1151",
        "code_sia": "NGA",
        "type_id": 77,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Sensor Trouble",
        "description_original": "Sensor Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "75",
        "code_cid": "1380",
        "code_sia": "NGT",
        "type_id": 79,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Flood Alert",
        "description_original": "Flood Alert",
        "description_placeholder_arguments": [],
        "code_vis": "77",
        "code_cid": "1154",
        "code_sia": "NWA",
        "type_id": 81,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Fail To Arm (Auto)",
        "description_original": "Fail To Arm (Auto)",
        "description_placeholder_arguments": [],
        "code_vis": "86",
        "code_cid": "1455",
        "code_sia": "NOT",
        "type_id": 90,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Fail To Set (By User)",
        "description_original": "Fail To Set (By User)",
        "description_placeholder_arguments": [],
        "code_vis": "93",
        "code_cid": "1454",
        "code_sia": "NCI",
        "type_id": 98,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Wrong Password",
        "description_original": "Wrong Password",
        "description_placeholder_arguments": [],
        "code_vis": "98",
        "code_cid": "1795",
        "code_sia": "000",
        "type_id": 105,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Not Sys Event",
        "description_original": "Not Sys Event",
        "description_placeholder_arguments": [],
        "code_vis": "99",
        "code_cid": "1794",
        "code_sia": "000",
        "type_id": 106,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Not Sys Event",
        "description_original": "Not Sys Event",
        "description_placeholder_arguments": [],
        "code_vis": "100",
        "code_cid": "1139",
        "code_sia": "NBV",
        "type_id": 107,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Freezer",
        "description_original": "Freezer",
        "description_placeholder_arguments": [],
        "code_vis": "101",
        "code_cid": "1152",
        "code_sia": "NZT",
        "type_id": 108,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Freezing",
        "description_original": "Freezing",
        "description_placeholder_arguments": [],
        "code_vis": "103",
        "code_cid": "1153",
        "code_sia": "NZA",
        "type_id": 110,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Cold",
        "description_original": "Cold",
        "description_placeholder_arguments": [],
        "code_vis": "105",
        "code_cid": "1159",
        "code_sia": "NKA",
        "type_id": 112,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Hot",
        "description_original": "Hot",
        "description_placeholder_arguments": [],
        "code_vis": "107",
        "code_cid": "1158",
        "code_sia": "NKA",
        "type_id": 114,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Probe Trouble",
        "description_original": "Probe Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "109",
        "code_cid": "1380",
        "code_sia": "NKT",
        "type_id": 116,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Probe Trouble",
        "description_original": "Probe Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "109",
        "code_cid": "1902",
        "code_sia": "NKT",
        "type_id": 117,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Masking",
        "description_original": "Masking",
        "description_placeholder_arguments": [],
        "code_vis": "111",
        "code_cid": "1380",
        "code_sia": "NUT",
        "type_id": 120,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Masking",
        "description_original": "Masking",
        "description_placeholder_arguments": [],
        "code_vis": "111",
        "code_cid": "1901",
        "code_sia": "NUT",
        "type_id": 121,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Repeater Low Battery",
        "description_original": "Repeater Low Battery",
        "description_placeholder_arguments": [],
        "code_vis": "113",
        "code_cid": "1384",
        "code_sia": "NXT",
        "type_id": 124,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Repeater Inactive",
        "description_original": "Repeater Inactive",
        "description_placeholder_arguments": [],
        "code_vis": "115",
        "code_cid": "1381",
        "code_sia": "NBZ",
        "type_id": 126,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "One Way Comm. Trbl",
        "description_original": "One Way Comm. Trbl",
        "description_placeholder_arguments": [],
        "code_vis": "121",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 132,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Basic keypad inactive",
        "description_original": "Basic keypad inactive",
        "description_placeholder_arguments": [],
        "code_vis": "132",
        "code_cid": "1381",
        "code_sia": "NBZ",
        "type_id": 143,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Heat Trouble",
        "description_original": "Heat Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "138",
        "code_cid": "1380",
        "code_sia": "NKT",
        "type_id": 149,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Gas Alert",
        "description_original": "Gas Alert",
        "description_placeholder_arguments": [],
        "code_vis": "139",
        "code_cid": "1151",
        "code_sia": "NGA",
        "type_id": 150,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "CO Trouble",
        "description_original": "CO Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "141",
        "code_cid": "1380",
        "code_sia": "NGT",
        "type_id": 152,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Self Test Trouble",
        "description_original": "Self Test Trouble",
        "description_placeholder_arguments": [],
        "code_vis": "145",
        "code_cid": "1389",
        "code_sia": "NYX",
        "type_id": 156,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "PSU Failure",
        "description_original": "PSU Failure",
        "description_placeholder_arguments": [],
        "code_vis": "155",
        "code_cid": "1337",
        "code_sia": "NYP",
        "type_id": 165,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Telephone Line Failure",
        "description_original": "Telephone Line Failure",
        "description_placeholder_arguments": [],
        "code_vis": "157",
        "code_cid": "1351",
        "code_sia": "NLT",
        "type_id": 167,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "EXP33 Missing",
        "description_original": "EXP33 Missing",
        "description_placeholder_arguments": [],
        "code_vis": "159",
        "code_cid": "1381",
        "code_sia": "NBZ",
        "type_id": 169,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Freezer trouble",
        "description_original": "Freezer trouble",
        "description_placeholder_arguments": [],
        "code_vis": "163",
        "code_cid": "1393",
        "code_sia": "NZA",
        "type_id": 177,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Supervision (Inactive)",
        "description_original": "Supervision (Inactive)",
        "description_placeholder_arguments": [],
        "code_vis": "167",
        "code_cid": "1381",
        "code_sia": "NBZ",
        "type_id": 188,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      }
    ]
  },
  {
    "profile": {
      "id": "EP_ALARM",
      "description": "Alarm",
      "description_original": "Alarm"
    },
    "events": [
      {
        "description": "Interior Alarm",
        "description_original": "Interior Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "1",
        "code_cid": "1132",
        "code_sia": "NBA",
        "type_id": 1,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Perimeter Alarm",
        "description_original": "Perimeter Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "2",
        "code_cid": "1131",
        "code_sia": "NBA",
        "type_id": 2,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Delay Alarm",
        "description_original": "Delay Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "3",
        "code_cid": "1134",
        "code_sia": "NBA",
        "type_id": 3,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "24h Silent Alarm",
        "description_original": "24h Silent Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "4",
        "code_cid": "1122",
        "code_sia": "NBA",
        "type_id": 4,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Panic",
        "description_original": "Panic",
        "description_placeholder_arguments": [],
        "code_vis": "4",
        "code_cid": "1133",
        "code_sia": "NBA",
        "type_id": 5,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "24h Audible Alarm",
        "description_original": "24h Audible Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "5",
        "code_cid": "1123",
        "code_sia": "NBA",
        "type_id": 6,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Panic",
        "description_original": "Panic",
        "description_placeholder_arguments": [],
        "code_vis": "5",
        "code_cid": "1133",
        "code_sia": "NBA",
        "type_id": 7,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Tamper",
        "description_original": "Tamper",
        "description_placeholder_arguments": [],
        "code_vis": "6",
        "code_cid": "1383",
        "code_sia": "NTA",
        "type_id": 8,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Control Panel Tamper",
        "description_original": "Control Panel Tamper",
        "description_placeholder_arguments": [],
        "code_vis": "7",
        "code_cid": "1137",
        "code_sia": "NTA",
        "type_id": 9,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Tamper Alarm",
        "description_original": "Tamper Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "8",
        "code_cid": "1383",
        "code_sia": "NTA",
        "type_id": 10,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Tamper Alarm",
        "description_original": "Tamper Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "9",
        "code_cid": "1383",
        "code_sia": "NTA",
        "type_id": 11,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Panic",
        "description_original": "Panic",
        "description_placeholder_arguments": [],
        "code_vis": "11",
        "code_cid": "1120",
        "code_sia": "NPA",
        "type_id": 13,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Panic From Control Panel",
        "description_original": "Panic From Control Panel",
        "description_placeholder_arguments": [],
        "code_vis": "12",
        "code_cid": "1120",
        "code_sia": "NPA",
        "type_id": 14,
        "label": "EL_PANEL_ALARM",
        "label_description": "EL_PANEL_ALARM"
      },
      {
        "description": "Confirm Alarm",
        "description_original": "Confirm Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "14",
        "code_cid": "1139",
        "code_sia": "NBV",
        "type_id": 16,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Fast zone open event",
        "description_original": "Fast zone open event",
        "description_placeholder_arguments": [],
        "code_vis": "16",
        "code_cid": "1789",
        "code_sia": "000",
        "type_id": 18,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Recent Close",
        "description_original": "Recent Close",
        "description_placeholder_arguments": [],
        "code_vis": "31",
        "code_cid": "1459",
        "code_sia": "NCR",
        "type_id": 35,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Fire",
        "description_original": "Fire",
        "description_placeholder_arguments": [],
        "code_vis": "32",
        "code_cid": "1110",
        "code_sia": "NFA",
        "type_id": 36,
        "label": "EL_PANEL_ALARM",
        "label_description": "EL_PANEL_ALARM"
      },
      {
        "description": "Emergency",
        "description_original": "Emergency",
        "description_placeholder_arguments": [],
        "code_vis": "35",
        "code_cid": "1101",
        "code_sia": "NQA",
        "type_id": 39,
        "label": "EL_PANEL_ALARM",
        "label_description": "EL_PANEL_ALARM"
      },
      {
        "description": "Repeater Tamper",
        "description_original": "Repeater Tamper",
        "description_placeholder_arguments": [],
        "code_vis": "117",
        "code_cid": "1383",
        "code_sia": "NTA",
        "type_id": 128,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Outdoor Zone Alarmed",
        "description_original": "Outdoor Zone Alarmed",
        "description_placeholder_arguments": [],
        "code_vis": "123",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 134,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Guard Key-Box Alarm",
        "description_original": "Guard Key-Box Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "125",
        "code_cid": "1220",
        "code_sia": "NBA",
        "type_id": 136,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Basic keypad tamper",
        "description_original": "Basic keypad tamper",
        "description_placeholder_arguments": [],
        "code_vis": "134",
        "code_cid": "1383",
        "code_sia": "NTA",
        "type_id": 145,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Heat",
        "description_original": "Heat",
        "description_placeholder_arguments": [],
        "code_vis": "136",
        "code_cid": "1114",
        "code_sia": "NKA",
        "type_id": 147,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Confirm Panic",
        "description_original": "Confirm Panic",
        "description_placeholder_arguments": [],
        "code_vis": "147",
        "code_cid": "1129",
        "code_sia": "NHV",
        "type_id": 158,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "GSM Antenna Tamper",
        "description_original": "GSM Antenna Tamper",
        "description_placeholder_arguments": [],
        "code_vis": "161",
        "code_cid": "1137",
        "code_sia": "NTA",
        "type_id": 171,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Event pending",
        "description_original": "Event pending",
        "description_placeholder_arguments": [],
        "code_vis": "997",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 997,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      }
    ]
  },
  {
    "profile": {
      "id": "EP_RESTORE",
      "description": "Restore",
      "description_original": "Restore"
    },
    "events": [
      {
        "description": "Interior Restore",
        "description_original": "Interior Restore",
        "description_placeholder_arguments": [],
        "code_vis": "17",
        "code_cid": "3132",
        "code_sia": "NBR",
        "type_id": 19,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Perimeter Restore",
        "description_original": "Perimeter Restore",
        "description_placeholder_arguments": [],
        "code_vis": "18",
        "code_cid": "3131",
        "code_sia": "NBR",
        "type_id": 20,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Delay Restore",
        "description_original": "Delay Restore",
        "description_placeholder_arguments": [],
        "code_vis": "19",
        "code_cid": "3134",
        "code_sia": "NBR",
        "type_id": 21,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "24h Silent Restore",
        "description_original": "24h Silent Restore",
        "description_placeholder_arguments": [],
        "code_vis": "20",
        "code_cid": "3122",
        "code_sia": "NBR",
        "type_id": 22,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Panic Restore",
        "description_original": "Panic Restore",
        "description_placeholder_arguments": [],
        "code_vis": "20",
        "code_cid": "3133",
        "code_sia": "NBR",
        "type_id": 23,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "24h Audible Restore",
        "description_original": "24h Audible Restore",
        "description_placeholder_arguments": [],
        "code_vis": "21",
        "code_cid": "3123",
        "code_sia": "NBR",
        "type_id": 24,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Panic Restore",
        "description_original": "Panic Restore",
        "description_placeholder_arguments": [],
        "code_vis": "21",
        "code_cid": "3133",
        "code_sia": "NBR",
        "type_id": 25,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Tamper Restore",
        "description_original": "Tamper Restore",
        "description_placeholder_arguments": [],
        "code_vis": "22",
        "code_cid": "3383",
        "code_sia": "NTR",
        "type_id": 26,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Control Panel Tamper Restore",
        "description_original": "Control Panel Tamper Restore",
        "description_placeholder_arguments": [],
        "code_vis": "23",
        "code_cid": "3137",
        "code_sia": "NTR",
        "type_id": 27,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Tamper Restore",
        "description_original": "Tamper Restore",
        "description_placeholder_arguments": [],
        "code_vis": "24",
        "code_cid": "3383",
        "code_sia": "NTR",
        "type_id": 28,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Fast zone close event",
        "description_original": "Fast zone close event",
        "description_placeholder_arguments": [],
        "code_vis": "25",
        "code_cid": "3789",
        "code_sia": "000",
        "type_id": 29,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Communication Restore",
        "description_original": "Communication Restore",
        "description_placeholder_arguments": [],
        "code_vis": "26",
        "code_cid": "3383",
        "code_sia": "NTR",
        "type_id": 30,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Cancel Alarm",
        "description_original": "Cancel Alarm",
        "description_placeholder_arguments": [],
        "code_vis": "27",
        "code_cid": "1406",
        "code_sia": "NBC",
        "type_id": 31,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "General Restore",
        "description_original": "General Restore",
        "description_placeholder_arguments": [],
        "code_vis": "28",
        "code_cid": "1799",
        "code_sia": "000",
        "type_id": 32,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Trouble Restore",
        "description_original": "Trouble Restore",
        "description_placeholder_arguments": [],
        "code_vis": "29",
        "code_cid": "3373",
        "code_sia": "NFJ",
        "type_id": 33,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Fire Restore",
        "description_original": "Fire Restore",
        "description_placeholder_arguments": [],
        "code_vis": "33",
        "code_cid": "3110",
        "code_sia": "NFR",
        "type_id": 37,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Panic Restore",
        "description_original": "Panic Restore",
        "description_placeholder_arguments": [],
        "code_vis": "38",
        "code_cid": "3120",
        "code_sia": "NPR",
        "type_id": 42,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Supervision Restore (Active)",
        "description_original": "Supervision Restore (Active)",
        "description_placeholder_arguments": [],
        "code_vis": "40",
        "code_cid": "3381",
        "code_sia": "000",
        "type_id": 44,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Low Battery Restore",
        "description_original": "Low Battery Restore",
        "description_placeholder_arguments": [],
        "code_vis": "42",
        "code_cid": "3384",
        "code_sia": "NXR",
        "type_id": 46,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "AC Restore",
        "description_original": "AC Restore",
        "description_placeholder_arguments": [],
        "code_vis": "44",
        "code_cid": "3301",
        "code_sia": "NAR",
        "type_id": 48,
        "label": "EL_AC_FAIL",
        "label_description": "EL_AC_FAIL"
      },
      {
        "description": "Control Panel Low Battery Restore",
        "description_original": "Control Panel Low Battery Restore",
        "description_placeholder_arguments": [],
        "code_vis": "46",
        "code_cid": "3302",
        "code_sia": "NYR",
        "type_id": 50,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "RF Jamming Restore",
        "description_original": "RF Jamming Restore",
        "description_placeholder_arguments": [],
        "code_vis": "48",
        "code_cid": "3344",
        "code_sia": "NBR",
        "type_id": 52,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Communications Restore",
        "description_original": "Communications Restore",
        "description_placeholder_arguments": [],
        "code_vis": "50",
        "code_cid": "3350",
        "code_sia": "NLR",
        "type_id": 54,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Telephone Line Restore",
        "description_original": "Telephone Line Restore",
        "description_placeholder_arguments": [],
        "code_vis": "52",
        "code_cid": "3351",
        "code_sia": "NLR",
        "type_id": 56,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Fuse Restore",
        "description_original": "Fuse Restore",
        "description_placeholder_arguments": [],
        "code_vis": "55",
        "code_cid": "3321",
        "code_sia": "NYH",
        "type_id": 59,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Keyfob Battery Restore",
        "description_original": "Keyfob Battery Restore",
        "description_placeholder_arguments": [],
        "code_vis": "57",
        "code_cid": "3384",
        "code_sia": "NXR",
        "type_id": 61,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Remote Commander Battery Restore",
        "description_original": "Remote Commander Battery Restore",
        "description_placeholder_arguments": [],
        "code_vis": "61",
        "code_cid": "3384",
        "code_sia": "NXR",
        "type_id": 65,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Remote Commander Active",
        "description_original": "Remote Commander Active",
        "description_placeholder_arguments": [],
        "code_vis": "63",
        "code_cid": "3381",
        "code_sia": "000",
        "type_id": 67,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Battery Restore",
        "description_original": "Battery Restore",
        "description_placeholder_arguments": [],
        "code_vis": "68",
        "code_cid": "3384",
        "code_sia": "NXR",
        "type_id": 72,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "AC Restore",
        "description_original": "AC Restore",
        "description_placeholder_arguments": [],
        "code_vis": "70",
        "code_cid": "3301",
        "code_sia": "NAR",
        "type_id": 74,
        "label": "EL_AC_FAIL",
        "label_description": "EL_AC_FAIL"
      },
      {
        "description": "Supervision Restore (Active)",
        "description_original": "Supervision Restore (Active)",
        "description_placeholder_arguments": [],
        "code_vis": "72",
        "code_cid": "3381",
        "code_sia": "000",
        "type_id": 76,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Gas Alert Restore",
        "description_original": "Gas Alert Restore",
        "description_placeholder_arguments": [],
        "code_vis": "74",
        "code_cid": "3151",
        "code_sia": "NGR",
        "type_id": 78,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Sensor Trouble Restore",
        "description_original": "Sensor Trouble Restore",
        "description_placeholder_arguments": [],
        "code_vis": "76",
        "code_cid": "3380",
        "code_sia": "NGJ",
        "type_id": 80,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Flood Alert Restore",
        "description_original": "Flood Alert Restore",
        "description_placeholder_arguments": [],
        "code_vis": "78",
        "code_cid": "3154",
        "code_sia": "NWR",
        "type_id": 82,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Freezer Restore",
        "description_original": "Freezer Restore",
        "description_placeholder_arguments": [],
        "code_vis": "102",
        "code_cid": "3152",
        "code_sia": "NZJ",
        "type_id": 109,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Freezing Restore",
        "description_original": "Freezing Restore",
        "description_placeholder_arguments": [],
        "code_vis": "104",
        "code_cid": "3153",
        "code_sia": "NZH",
        "type_id": 111,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Cold Restore",
        "description_original": "Cold Restore",
        "description_placeholder_arguments": [],
        "code_vis": "106",
        "code_cid": "3159",
        "code_sia": "NKH",
        "type_id": 113,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Hot Restore",
        "description_original": "Hot Restore",
        "description_placeholder_arguments": [],
        "code_vis": "108",
        "code_cid": "3158",
        "code_sia": "NKH",
        "type_id": 115,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Probe Trouble Restore",
        "description_original": "Probe Trouble Restore",
        "description_placeholder_arguments": [],
        "code_vis": "110",
        "code_cid": "3380",
        "code_sia": "NKJ",
        "type_id": 118,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Probe Trouble Restore",
        "description_original": "Probe Trouble Restore",
        "description_placeholder_arguments": [],
        "code_vis": "110",
        "code_cid": "3902",
        "code_sia": "NKJ",
        "type_id": 119,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Masking Restore",
        "description_original": "Masking Restore",
        "description_placeholder_arguments": [],
        "code_vis": "112",
        "code_cid": "3380",
        "code_sia": "NUJ",
        "type_id": 122,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Masking Restore",
        "description_original": "Masking Restore",
        "description_placeholder_arguments": [],
        "code_vis": "112",
        "code_cid": "3901",
        "code_sia": "NUJ",
        "type_id": 123,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Repeater Battery Restore",
        "description_original": "Repeater Battery Restore",
        "description_placeholder_arguments": [],
        "code_vis": "114",
        "code_cid": "3384",
        "code_sia": "NXR",
        "type_id": 125,
        "label": "EL_BATTERY",
        "label_description": "EL_BATTERY"
      },
      {
        "description": "Repeater Active",
        "description_original": "Repeater Active",
        "description_placeholder_arguments": [],
        "code_vis": "116",
        "code_cid": "3381",
        "code_sia": "000",
        "type_id": 127,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Repeater Tamper Restore",
        "description_original": "Repeater Tamper Restore",
        "description_placeholder_arguments": [],
        "code_vis": "118",
        "code_cid": "3383",
        "code_sia": "NTR",
        "type_id": 129,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "One Way Comm. Rstr",
        "description_original": "One Way Comm. Rstr",
        "description_placeholder_arguments": [],
        "code_vis": "122",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 133,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Outdoor Zone Restored",
        "description_original": "Outdoor Zone Restored",
        "description_placeholder_arguments": [],
        "code_vis": "124",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 135,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Guard Key-Box Alarm Restore",
        "description_original": "Guard Key-Box Alarm Restore",
        "description_placeholder_arguments": [],
        "code_vis": "126",
        "code_cid": "3220",
        "code_sia": "NBR",
        "type_id": 137,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Basic keypad active",
        "description_original": "Basic keypad active",
        "description_placeholder_arguments": [],
        "code_vis": "133",
        "code_cid": "3381",
        "code_sia": "000",
        "type_id": 144,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Basic keypad tamper restore",
        "description_original": "Basic keypad tamper restore",
        "description_placeholder_arguments": [],
        "code_vis": "135",
        "code_cid": "3383",
        "code_sia": "NTR",
        "type_id": 146,
        "label": "EL_BURGLER",
        "label_description": "EL_BURGLER"
      },
      {
        "description": "Heat Restore",
        "description_original": "Heat Restore",
        "description_placeholder_arguments": [],
        "code_vis": "137",
        "code_cid": "3114",
        "code_sia": "NKH",
        "type_id": 148,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Gas Alert Restore",
        "description_original": "Gas Alert Restore",
        "description_placeholder_arguments": [],
        "code_vis": "140",
        "code_cid": "3151",
        "code_sia": "NGR",
        "type_id": 151,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "CO Trouble Restore",
        "description_original": "CO Trouble Restore",
        "description_placeholder_arguments": [],
        "code_vis": "142",
        "code_cid": "3380",
        "code_sia": "NGJ",
        "type_id": 153,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Self Test Trouble Restore",
        "description_original": "Self Test Trouble Restore",
        "description_placeholder_arguments": [],
        "code_vis": "146",
        "code_cid": "3389",
        "code_sia": "NYZ",
        "type_id": 157,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "PSU Restore",
        "description_original": "PSU Restore",
        "description_placeholder_arguments": [],
        "code_vis": "156",
        "code_cid": "3337",
        "code_sia": "NYQ",
        "type_id": 166,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Telephone Line Restore",
        "description_original": "Telephone Line Restore",
        "description_placeholder_arguments": [],
        "code_vis": "158",
        "code_cid": "3351",
        "code_sia": "NLR",
        "type_id": 168,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "EXP33 Active",
        "description_original": "EXP33 Active",
        "description_placeholder_arguments": [],
        "code_vis": "160",
        "code_cid": "3381",
        "code_sia": "000",
        "type_id": 170,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "GSM Antenna Tamper Restore",
        "description_original": "GSM Antenna Tamper Restore",
        "description_placeholder_arguments": [],
        "code_vis": "162",
        "code_cid": "3137",
        "code_sia": "NTR",
        "type_id": 172,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Freezer trouble restore",
        "description_original": "Freezer trouble restore",
        "description_placeholder_arguments": [],
        "code_vis": "164",
        "code_cid": "3393",
        "code_sia": "NZH",
        "type_id": 187,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Supervision Restore (Active)",
        "description_original": "Supervision Restore (Active)",
        "description_placeholder_arguments": [],
        "code_vis": "168",
        "code_cid": "3381",
        "code_sia": "000",
        "type_id": 189,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Disarm after alarm",
        "description_original": "Disarm after alarm",
        "description_placeholder_arguments": [],
        "code_vis": "189",
        "code_cid": "3140",
        "code_sia": "NOR",
        "type_id": 173,
        "label": "EL_DISARM",
        "label_description": "EL_DISARM"
      }
    ]
  },
  {
    "profile": {
      "id": "EP_OPEN_CLOSE",
      "description": "Open/Close",
      "description_original": "Open/Close"
    },
    "events": [
      {
        "description": "Disarm",
        "description_original": "Disarm",
        "description_placeholder_arguments": [],
        "code_vis": "37",
        "code_cid": "1401",
        "code_sia": "NOP",
        "type_id": 41,
        "label": "EL_DISARM",
        "label_description": "EL_DISARM"
      },
      {
        "description": "Arm Home",
        "description_original": "Arm Home",
        "description_placeholder_arguments": [],
        "code_vis": "81",
        "code_cid": "3441",
        "code_sia": "NCG",
        "type_id": 85,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Arm Away",
        "description_original": "Arm Away",
        "description_placeholder_arguments": [],
        "code_vis": "82",
        "code_cid": "3401",
        "code_sia": "NCL",
        "type_id": 86,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Quick Arm Home",
        "description_original": "Quick Arm Home",
        "description_placeholder_arguments": [],
        "code_vis": "83",
        "code_cid": "3441",
        "code_sia": "NCG",
        "type_id": 87,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Quick Arm Away",
        "description_original": "Quick Arm Away",
        "description_placeholder_arguments": [],
        "code_vis": "84",
        "code_cid": "3408",
        "code_sia": "NCL",
        "type_id": 88,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Disarm",
        "description_original": "Disarm",
        "description_placeholder_arguments": [],
        "code_vis": "85",
        "code_cid": "1401",
        "code_sia": "NOP",
        "type_id": 89,
        "label": "EL_DISARM",
        "label_description": "EL_DISARM"
      },
      {
        "description": "Force Arm Away",
        "description_original": "Force Arm Away",
        "description_placeholder_arguments": [],
        "code_vis": "89",
        "code_cid": "3456",
        "code_sia": "NCF",
        "type_id": 93,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Auto Arm Away",
        "description_original": "Auto Arm Away",
        "description_placeholder_arguments": [],
        "code_vis": "90",
        "code_cid": "3403",
        "code_sia": "NCP",
        "type_id": 94,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Auto Arm Away",
        "description_original": "Auto Arm Away",
        "description_placeholder_arguments": [],
        "code_vis": "90",
        "code_cid": "1403",
        "code_sia": "NCP",
        "type_id": 95,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Instant Away",
        "description_original": "Instant Away",
        "description_placeholder_arguments": [],
        "code_vis": "91",
        "code_cid": "3490",
        "code_sia": "000",
        "type_id": 96,
        "label": "EL_ARM",
        "label_description": "EL_ARM"
      },
      {
        "description": "Door Open",
        "description_original": "Door Open",
        "description_placeholder_arguments": [],
        "code_vis": "94",
        "code_cid": "1426",
        "code_sia": "NEA",
        "type_id": 99,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Door Open",
        "description_original": "Door Open",
        "description_placeholder_arguments": [],
        "code_vis": "94",
        "code_cid": "1374",
        "code_sia": "NEA",
        "type_id": 100,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      }
    ]
  },
  {
    "profile": {
      "id": "EP_ONLINE",
      "description": "Online",
      "description_original": "Online"
    },
    "events": [
      {
        "description": "GPRS module has come online",
        "description_original": "GPRS module has come online",
        "description_placeholder_arguments": [],
        "code_vis": "992",
        "code_cid": "3352",
        "code_sia": "NYC",
        "type_id": 992,
        "label": "EL_ONLINE",
        "label_description": "EL_ONLINE"
      },
      {
        "description": "BBA module has come online",
        "description_original": "BBA module has come online",
        "description_placeholder_arguments": [],
        "code_vis": "994",
        "code_cid": "3353",
        "code_sia": "NYE",
        "type_id": 994,
        "label": "EL_ONLINE",
        "label_description": "EL_ONLINE"
      },
      {
        "description": "PLINK module has come online",
        "description_original": "PLINK module has come online",
        "description_placeholder_arguments": [],
        "code_vis": "996",
        "code_cid": "3354",
        "code_sia": "NYG",
        "type_id": 996,
        "label": "EL_ONLINE",
        "label_description": "EL_ONLINE"
      },
      {
        "description": "Panel has come online",
        "description_original": "Panel has come online",
        "description_placeholder_arguments": [],
        "code_vis": "999",
        "code_cid": "3356",
        "code_sia": "NYK",
        "type_id": 999,
        "label": "EL_ONLINE",
        "label_description": "EL_ONLINE"
      }
    ]
  },
  {
    "profile": {
      "id": "EP_OFFLINE",
      "description": "Offline",
      "description_original": "Offline"
    },
    "events": [
      {
        "description": "GPRS module has gone offline",
        "description_original": "GPRS module has gone offline",
        "description_placeholder_arguments": [],
        "code_vis": "991",
        "code_cid": "1352",
        "code_sia": "NYB",
        "type_id": 991,
        "label": "EL_OFFLINE",
        "label_description": "EL_OFFLINE"
      },
      {
        "description": "BBA module has gone offline",
        "description_original": "BBA module has gone offline",
        "description_placeholder_arguments": [],
        "code_vis": "993",
        "code_cid": "1353",
        "code_sia": "NYD",
        "type_id": 993,
        "label": "EL_OFFLINE",
        "label_description": "EL_OFFLINE"
      },
      {
        "description": "PLINK module has gone offline",
        "description_original": "PLINK module has gone offline",
        "description_placeholder_arguments": [],
        "code_vis": "995",
        "code_cid": "1354",
        "code_sia": "NYF",
        "type_id": 995,
        "label": "EL_OFFLINE",
        "label_description": "EL_OFFLINE"
      },
      {
        "description": "Panel has gone offline",
        "description_original": "Panel has gone offline",
        "description_placeholder_arguments": [],
        "code_vis": "998",
        "code_cid": "1356",
        "code_sia": "NYS",
        "type_id": 998,
        "label": "EL_OFFLINE",
        "label_description": "EL_OFFLINE"
      },
      {
        "description": "Panel has gone offline after AC Fail",
        "description_original": "Panel has gone offline after AC Fail",
        "description_placeholder_arguments": [],
        "code_vis": "1000",
        "code_cid": "1750",
        "code_sia": "NAZ",
        "type_id": 1000,
        "label": "EL_OFFLINE",
        "label_description": "EL_OFFLINE"
      }
    ]
  },
  {
    "profile": {
      "id": "EP_NOTICE",
      "description": "Notice",
      "description_original": "Notice"
    },
    "events": [
      {
        "description": "Remove User",
        "description_original": "Remove User",
        "description_placeholder_arguments": [],
        "code_vis": "36",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 40,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Auto Test",
        "description_original": "Auto Test",
        "description_placeholder_arguments": [],
        "code_vis": "53",
        "code_cid": "1602",
        "code_sia": "NRP",
        "type_id": 57,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Engineer Reset",
        "description_original": "Engineer Reset",
        "description_placeholder_arguments": [],
        "code_vis": "58",
        "code_cid": "3313",
        "code_sia": "NRN",
        "type_id": 62,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Enter To Test Mode",
        "description_original": "Enter To Test Mode",
        "description_placeholder_arguments": [],
        "code_vis": "87",
        "code_cid": "1607",
        "code_sia": "NRX",
        "type_id": 91,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Exit From Test Mode",
        "description_original": "Exit From Test Mode",
        "description_placeholder_arguments": [],
        "code_vis": "88",
        "code_cid": "3607",
        "code_sia": "NRY",
        "type_id": 92,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Bypass",
        "description_original": "Bypass",
        "description_placeholder_arguments": [],
        "code_vis": "92",
        "code_cid": "1570",
        "code_sia": "NBB",
        "type_id": 97,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Communication Established By Control Panel",
        "description_original": "Communication Established By Control Panel",
        "description_placeholder_arguments": [],
        "code_vis": "95",
        "code_cid": "1798",
        "code_sia": "000",
        "type_id": 101,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "System Reset",
        "description_original": "System Reset",
        "description_placeholder_arguments": [],
        "code_vis": "96",
        "code_cid": "1797",
        "code_sia": "000",
        "type_id": 102,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Installer Programming",
        "description_original": "Installer Programming",
        "description_placeholder_arguments": [],
        "code_vis": "97",
        "code_cid": "1627",
        "code_sia": "NLB",
        "type_id": 103,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Installer Programming",
        "description_original": "Installer Programming",
        "description_placeholder_arguments": [],
        "code_vis": "97",
        "code_cid": "1793",
        "code_sia": "000",
        "type_id": 104,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Siren Test End",
        "description_original": "Siren Test End",
        "description_placeholder_arguments": [],
        "code_vis": "119",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 130,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Devices Test End",
        "description_original": "Devices Test End",
        "description_placeholder_arguments": [],
        "code_vis": "120",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 131,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Time/date change",
        "description_original": "Time/date change",
        "description_placeholder_arguments": [],
        "code_vis": "127",
        "code_cid": "1625",
        "code_sia": "NJT",
        "type_id": 138,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "System shutdown",
        "description_original": "System shutdown",
        "description_placeholder_arguments": [],
        "code_vis": "128",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 139,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "System powerup",
        "description_original": "System powerup",
        "description_placeholder_arguments": [],
        "code_vis": "129",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 140,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Missed reminder",
        "description_original": "Missed reminder",
        "description_placeholder_arguments": [],
        "code_vis": "130",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 141,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Pendant test fail",
        "description_original": "Pendant test fail",
        "description_placeholder_arguments": [],
        "code_vis": "131",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 142,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Exit Installer Programming",
        "description_original": "Exit Installer Programming",
        "description_placeholder_arguments": [],
        "code_vis": "143",
        "code_cid": "1628",
        "code_sia": "NLX",
        "type_id": 154,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Installer Programming Locally",
        "description_original": "Installer Programming Locally",
        "description_placeholder_arguments": [],
        "code_vis": "144",
        "code_cid": "1627",
        "code_sia": "NLB",
        "type_id": 155,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Transmitter man down",
        "description_original": "Transmitter man down",
        "description_placeholder_arguments": [],
        "code_vis": "148",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 159,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Soak Test Fail",
        "description_original": "Soak Test Fail",
        "description_placeholder_arguments": [],
        "code_vis": "149",
        "code_cid": "1391",
        "code_sia": "NBX",
        "type_id": 160,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Soak Test Fail (Fire)",
        "description_original": "Soak Test Fail (Fire)",
        "description_placeholder_arguments": [],
        "code_vis": "150",
        "code_cid": "1391",
        "code_sia": "NFX",
        "type_id": 161,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Soak Test Fail (Gas)",
        "description_original": "Soak Test Fail (Gas)",
        "description_placeholder_arguments": [],
        "code_vis": "151",
        "code_cid": "1391",
        "code_sia": "NGX",
        "type_id": 162,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "SW-UPGRADE FAIL",
        "description_original": "SW-UPGRADE FAIL",
        "description_placeholder_arguments": [],
        "code_vis": "152",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 163,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "SW-UPGRADE PASS",
        "description_original": "SW-UPGRADE PASS",
        "description_placeholder_arguments": [],
        "code_vis": "153",
        "code_cid": "0000",
        "code_sia": "000",
        "type_id": 164,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "RRI test is failed",
        "description_original": "RRI test is failed",
        "description_placeholder_arguments": [],
        "code_vis": "190",
        "code_cid": "1666",
        "code_sia": "NTF",
        "type_id": 174,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "RRI test is succeeded",
        "description_original": "RRI test is succeeded",
        "description_placeholder_arguments": [],
        "code_vis": "191",
        "code_cid": "3666",
        "code_sia": "NTO",
        "type_id": 175,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      },
      {
        "description": "Manual trigger test report",
        "description_original": "Manual trigger test report",
        "description_placeholder_arguments": [],
        "code_vis": "990",
        "code_cid": "1601",
        "code_sia": "NTC",
        "type_id": 176,
        "label": "EL_NONE",
        "label_description": "EL_NONE"
      }
    ]
  },
  {
    "profile": {
      "id": "EP_DURESS",
      "description": "Duress",
      "description_original": "Duress"
    },
    "events": [
      {
        "description": "Duress",
        "description_original": "Duress",
        "description_placeholder_arguments": [],
        "code_vis": "13",
        "code_cid": "1121",
        "code_sia": "NHA",
        "type_id": 15,
        "label": "EL_PANEL_ALARM",
        "label_description": "EL_PANEL_ALARM"
      }
    ]
  }
]
```
