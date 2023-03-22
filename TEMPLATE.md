# Namespace (Teams, Projects, etc.) - Short Name
### Short, general description

URL: `https://create.fortnite.com/XXXXXXXXXXXXXXXX` \
Method: `GET/POST/DELETE/UPDATE/OPTIONS/etc.` \
Authentication: `YES (specify what type in brackets)/NO`
Permissions required:
  - Some:Permission CREATE
  - Some:Permission UPDATE

#### Request Body:
```json
{}
```

### Responses
#### Success:
```json
{
  "some": "response"
}
```

#### Error:
```json
{
  "errorCode": "errors.com.epicgames.creator-portal-backend.XXXXXXXXXXXXX",
  "errorMessage": "XXXXXXXXXXXXXXXXX"
}
```
