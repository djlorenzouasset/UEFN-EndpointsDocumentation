# Projects - Edit Project's Metadata

URL: `https://content-service.bfda.live.use1a.on.epicgames.com/api/content/v2/project/[projectid]/meta` \
ProjectID Example: `6a7b8e1f-3d09-bd2c-f5a3-9e4d2c0e7a6f` \
Method: `PUT` \
Authentication: `YES (Bearer Token)`

### Payload:
```json
{
    "locale": "en-us",
    "title": "",
    "description": ""
}
```

### Responses
#### Success:
```json
{
   "projectId": "projectid",
   "accountId": "accountid",
   "title": "projecttitle",
   "hasStar": true,
   "access": {
      "read": true,
      "edit": true,
      "publish": true,
      "operate": true,
      "admin": true
   }
}
```

#### Error:
```json
{
    "host": "content-service.bfda.live.use1a.on.epicgames.com",
    "method": "GET",
    "path": "/api/content/v2/project/{projectId}/meta",
    "errorCode": "errors.com.epicgames.content-service.XXXXXXXXXXXXXXXXXXXXXX",
    "errorMessage": "XXXXXXXXXXXXXXXXXXXXXXXXXX"
}
```
