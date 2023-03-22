# Teams - Create Team
### Create a UEFN Work Team

URL: `https://create.fortnite.com/api/vk/v1/teams` \
Method: `POST` \
Authentication: `YES (EG1 cookie and CSRF)`

#### Request Body:
```json
{
  "name": "Team Name",
  "description": "Team Description",
  "emailDomains": []
}
```

### Responses
#### Success:
```
Currently unknown.
```

#### Error:
```json
{
  "errorCode": "errors.com.epicgames.creator-portal-backend.XXXXXXXXXXXXX",
  "errorMessage": "XXXXXXXXXXXXXXXXX"
}
```
