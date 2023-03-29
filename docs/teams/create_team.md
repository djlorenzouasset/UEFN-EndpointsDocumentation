# Teams - Create Team

URL: `https://create.fortnite.com/api/vk/v1/teams` \
Method: `POST` \
Authentication: `YES (EG1 cookie and CSRF)`

Permissions required:
  - creator-portal:teams CREATE

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
