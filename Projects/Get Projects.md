# Teams - Create Team
### Create a UEFN Work Team

URL: `https://create.fortnite.com/api/vk/v1/projects` \
Method: `GET` \
Authentication: `YES (EG1 cookie and CSRF)`


### Responses
#### Success:
```json
{
    "limit": 100,
    "results": [
        {
            "projectId": "",
            "date": "",
            "info": {
                "owner": {
                    "type": "",
                    "id": "",
                    "name": ""
                },
                "linkCode": null,
                "title": "",
                "description": "",
                "sysMeta": {
                    "dataAuthority": {
                        "dataAuthority": "UEFN",
                        "hasUEFNData": true
                    }
                }
            },
            "is_starred": true,
            "public": false,
            "origin": "UEFN",
            "authority": "UEFN"
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
