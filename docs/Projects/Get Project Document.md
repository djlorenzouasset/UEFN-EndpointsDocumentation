# Projects - GET Project User Info
### Get UEFN Project Data/Document

URL: `https://content-service.bfda.live.use1a.on.epicgames.com/api/content/v2/project/[projectid]#` \
ProjectID Example: `6a7b8e1f-3d09-bd2c-f5a3-9e4d2c0e7a6f` \
Method: `GET` \
Authentication: `YES (Bearer Token)`


### Responses
#### Success:
```json
{
    "projectId": "projectid",
    "created": "time",
    "author": {
        "id": "accountid",
        "type": "type"
    },
    "owner": {
        "id": "accountid",
        "type": "type"
    },
    "meta": {
        "name": "projectname",
        "kind": "Island",
        "title": "projectname",
        "description": "",
        "key_art": "",
        "attributions": [],
        "locale": "en-US",
        "source_control": {
            "active": "Unreal Revision Control",
            "Unreal Revision Control": {
                "fileVersion": 1,
                "providerName": "Unreal Revision Control",
                "providerParameters": {}
            }
        }
    },
    "sysMeta": {
        "dataAuthority": {
            "dataAuthority": "UEFN",
            "hasUEFNData": true
        }
    },
    "privateLinks": {}
}
```

#### Error:
```json
{
    "host": "content-service.bfda.live.use1a.on.epicgames.com",
    "method": "GET",
    "path": "/api/content/v2/project/projectid",
    "errorCode": "errors.com.epicgames.content-service.auth_required",
    "errorMessage": "Bearer auth required."
}
```
