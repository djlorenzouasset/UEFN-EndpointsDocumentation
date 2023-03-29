# Projects - Edit Project's Metadata
### Edit a UEFN Work project

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
   "projectId":"projectid",
   "accountId":"accountid",
   "title":"projecttitle",
   "hasStar":true,
   "access":{
      "read":true,
      "edit":true,
      "publish":true,
      "operate":true,
      "admin":true
   }
}
```

#### Error:
```json
{
    "host": "content-service.bfda.live.use1a.on.epicgames.com",
    "method": "GET",
    "path": "/api/content/v2/project/3b118c78-117b-4eda-b500-f7553485d474/meta",
    "errorCode": "errors.com.epicgames.content-service.auth_required",
    "errorMessage": "Bearer auth required."
}
```
