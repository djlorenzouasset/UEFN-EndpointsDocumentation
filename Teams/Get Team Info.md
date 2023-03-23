# Teams - GET Team Info
### GET UEFN Work Team Info

URL: `https://create.fortnite.com/api/vk/v1/teams/:team_id` \
Method: `GET` \
Authentication: `YES (EG1 cookie and CSRF)`


### Responses
#### Success:
```json
{
    "teamId": "",
    "created": "",
    "updated": "",
    "name": "",
    "description": "",
    "owner": {
        "type": "account",
        "id": "",
        "name": ""
    },
    "memberCount": 1,
    "playtesterCount": 0,
    "publishingBrand": "",
    "playtestGroups": [],
    "limits": {
        "memberLimit": 30,
        "playtesterLimit": 50,
        "playtestGroupLimit": 5,
        "joinCodeLimit": 50
    },
    "membership": {
        "membershipId": "",
        "accountId": "",
        "displayName": "",
        "updated": "",
        "status": "accepted",
        "vkAccess": {
            "edit": true,
            "publish": true,
            "operate": true,
            "admin": true
        },
        "cpRole": "owner"
    }
}
```

#### Error:
```json
{
  "errorCode": "errors.com.epicgames.creator-portal-backend.XXXXXXXXXXXXX",
  "errorMessage": "XXXXXXXXXXXXXXXXX"
}
```
