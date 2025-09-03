# /rri_results

## Name
/rri_results

## Description
This method returns remote inspection results.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /rri_results`

## Example Response
```json
{
  "rri_timestamp": "2025-01-23 15:43:21",
  "tests": [
    {
      "test_type": 1,
      "state": "fail",
      "details": [
        {
          "detail_name": "Control Panel Tamper",
          "description": "Control Panel",
          "timestamp": "2025-01-23 11:21:55"
        }
      ]
    },
    {
      "test_type": 2,
      "state": "pass",
      "details": [
        {
          "detail_name": "Arm Away",
          "description": "Keyfob 1",
          "timestamp": "2025-01-21 14:58:34"
        }
      ]
    },
    {
      "test_type": 3,
      "state": "pass",
      "details": [
        {
          "detail_name": "",
          "description": "",
          "timestamp": ""
        }
      ]
    },
    {
      "test_type": 4,
      "state": "pass",
      "details": [
        {
          "detail_name": "",
          "description": "",
          "timestamp": ""
        }
      ]
    },
    {
      "test_type": 5,
      "state": "pass",
      "details": [
        {
          "detail_name": "",
          "description": "",
          "timestamp": ""
        }
      ]
    },
    {
      "test_type": 6,
      "state": "fail",
      "details": [
        {
          "detail_name": "120",
          "description": "120",
          "timestamp": "0000-00-00 00:00:00"
        }
      ]
    },
    {
      "test_type": 8,
      "state": "not_available",
      "details": [
        {
          "detail_name": "",
          "description": "",
          "timestamp": ""
        }
      ]
    },
    {
      "test_type": 9,
      "state": "pass",
      "details": [
        {
          "detail_name": "",
          "description": "",
          "timestamp": ""
        }
      ]
    },
    {
      "test_type": 10,
      "state": "pass",
      "details": [
        {
          "detail_name": "",
          "description": "",
          "timestamp": ""
        }
      ]
    }
  ]
}
```
