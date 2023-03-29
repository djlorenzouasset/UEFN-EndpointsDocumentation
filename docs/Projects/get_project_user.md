# Projects - GET Project User Info
### Get all UEFN Work projects

URL: `https://create.fortnite.com/api/vk/v1/projects/[projectid]/user` \
ProjectID Example: `6a7b8e1f-3d09-bd2c-f5a3-9e4d2c0e7a6f` \
Method: `GET` \
Authentication: `YES (EG1 cookie and CSRF)`


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
  "errorCode": "errors.com.epicgames.creator-portal-backend.XXXXXXXXXXXXX",
  "errorMessage": "XXXXXXXXXXXXXXXXX"
}
```
