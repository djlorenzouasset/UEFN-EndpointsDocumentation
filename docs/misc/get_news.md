# Creator Portal - Get List of News
> Gives you a list of the latest Creative news visible on the Creator Portal.

URL: `https://create.fortnite.com/api/cms/v1/articles` \
Method: `GET` \
Authentication: `NO` \
Language Support: `YES`

Permissions required:
 - None

Parameters:
```jsonc
{
    "slug": "", // optional parameter, can be passed for get a single post like "fortnite-creative-v24-30-update".
    "locale": "", // optional parameter, can be passed for set the language of the blogs data.
    "rootPageSlug": "blog-creator-portal"
}
```

### Responses
#### Success:
```json
{
    "blogList": [
      {
        "trending": false,
        "noTopImage": false,
        "redirect": {
          "code": "",
          "_type": ""
        },
        "image": "",
        "contentTypeSticky": false,
        "author": "",
        "enableLightbox": false,
        "_type": "",
        "alt": "",
        "shareImage": "",
        "hasSocialWidget": false,
        "title": "",
        "shareImageAlt": "",
        "content": "",
        "mobileThumbnailImage": "",
        "trendingImageAlt": "",
        "trendingImage": "",
        "mobileThumbnailImageAlt": "",
        "highlightImage": "",
        "sticky": false,
        "socialWidget": {
          "cta": {
            "_type": "",
            "theme": {
              "_type": ""
            }
          },
          "_type": "",
          "dateColor": ""
        },
        "featured": false,
        "date": "",
        "link": "",
        "_id": "",
        "pageMapping": "",
        "slug": "",
        "urlPattern": "",
        "locale": "",
        "noIndex": false,
        "_script": "",
        "category": [],
        "tags": [],
        "_metaTags": "",
        "catLocaleMap": {},
        "prevSlug": ""
      }
    ],
    "blogTotal": 19,
    "postCount": 13,
    "incrementCount": 8,
    "articlesToLoad": 13,
    "categoryTotals": {
      "all": 19
    },
    "category": null,
    "catLocaleMap": {},
    "ctaBlockData": {},
    "newsletter": {}
}
```
