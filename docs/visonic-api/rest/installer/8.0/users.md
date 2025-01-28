# /users

## Name
/users

## Description
This method returns a list of users registered with the panel.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

## Example Request
`GET /users`

## Example Response
```json
{
  "max_users_count": 8,
  "user_names": {
    "1": "Joe Bloggs",
    "2": "Joe Bloggs",
    "3": "Joe Bloggs",
    "4": "Joe Bloggs",
    "5": "Joe Bloggs"
  }
}
```