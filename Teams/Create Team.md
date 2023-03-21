# POST /api/vk/v1/teams
Host: `create.fortnite.com`<br>
Authentication required: `Yes (EG1 cookie and CSRF)`

Body:
```
{
  "name": "Team Name",
  "description": "Team Description",
  "emailDomains": [] // unknown
}
```

Success returns:<br>
```
Unknown.
```

Failure returns:<br>
```
{
  "errorCode": "errors.com.epicgames.creator-portal-backend.XXXXXXXXXXXXX",
  "errorMessage": "XXXXXXXXXXXXXXXXX"
}
