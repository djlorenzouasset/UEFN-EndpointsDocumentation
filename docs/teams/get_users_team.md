# Teams - GET Teams

URL: `https://create.fortnite.com/api/vk/v1/teams` \
Method: `GET` \
Authentication: `YES (EG1 cookie and CSRF)`

### Responses
#### Success:
```json
{
    "limit": 100,
    "results": [
        {
            "teamId": "",
            "name": "",
            "description": "",
            "owner": {
                "type": "",
                "id": "",
                "name": ""
            },
            "memberCount": 1,
            "playtesterCount": -1,
            "publishingBrand": "",
            "membership": {
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
        },
        null
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
