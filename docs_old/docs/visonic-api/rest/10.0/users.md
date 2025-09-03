# /users

## Name
/users

## Description
This method returns a list of users registered with the panel.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /users`

## Example Response
```json
{
  "max_users_count": 8,
  "users": [
    {
      "id": 1,
      "name": "Joe Bloggs 1",
      "partitions": [
        1,
        2,
        3
      ],
      "email": "joe1@bloggs.com"
    },
    {
      "id": 2,
      "name": "Joe Bloggs 2",
      "partitions": [
        1
      ],
      "email": "joe2@bloggs.com"
    }
}
```
