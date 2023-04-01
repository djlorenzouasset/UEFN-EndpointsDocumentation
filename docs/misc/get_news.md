# Creator Portal - Get List of News
> Gives you a list of the latest Creative news visible on the Creator Portal.
### Note: This URL changes every day, because it is using the Next API.

URL: `https://create.fortnite.com/_next/data/NopkUZQ4J7tvAlR0x11c7/en-US/news.json` \
Method: `GET` \
Authentication: `NO` \
Language Support: `NO`

Permissions required:
 - None

### Responses
#### Success:
```json
{
  "pageProps": {
    "teams": [],
    "locale": "en-US",
    "blogs": [
      {
        "title": "Title of the News Article",
        "_id": "ID of the news article",
        "date": "ISO Date of addition",
        "trendingImage": "https://cdn2.unrealengine.com/XXXXXXXXXXXXXXXXXX.jpg",
        "image": "https://cdn2.unrealengine.com/XXXXXXXXXXXXXXXXXX.jpg",
        "slug": "some-news-article"
      },
    ],
    "blogsTotal": 1
  },
  "canonicalUrl": "https://create.fortnite.com/news?team=personal"
}
```
