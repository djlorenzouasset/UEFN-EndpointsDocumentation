## Teams - Create Team: Create a UEFN Work Team

URL: https://create.fortnite.com/team \
Method: POST \
Authentication required: `Yes (EG1 cookie and CSRF)`

Request Body:
```jsonc
{
  "name": "Team Name",
  "description": "Team Description",
  "emailDomains": [] // unknown
}
```

The result is currently unknown

## On failure

```json
{
  "errorCode": "errors.com.epicgames.creator-portal-backend.XXXXXXXXXXXXX",
  "errorMessage": "XXXXXXXXXXXXXXXXX"
}
