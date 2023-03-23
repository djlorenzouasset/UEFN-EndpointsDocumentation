# Teams - GET Team Members
### GET all UEFN Work Team Members

URL: `https://create.fortnite.com/api/vk/v1/teams/:team_id/members` \
Method: `GET` \
Authentication: `YES (EG1 cookie and CSRF)`


### Responses
#### Success:
```json
{
    "limit": 100,
    "results": [
        {
            "membershipId": "",
            "accountId": "",
            "displayName": "",
            "status": "",
            "updated": "",
            "vkAccess": {
                "edit": true,
                "publish": true,
                "operate": true,
                "admin": true
            },
            "cpRole": "owner"
        }
    ]
}
```

#### Error:
```json
{
  "errorCode": "errors.com.epicgames.creator-portal-backend.XXXXXXXXXXXXX",
  "errorMessage": "XXXXXXXXXXXXXXXXX"
}
```
