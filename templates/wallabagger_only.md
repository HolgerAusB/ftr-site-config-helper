Sometimes Fulltext-RSS and/or wallabage UI are not able to fetch the content, because the domain is using some techniques to prevent this, e.g. JavaScript, Cloudflare service or simmilar.

Wallabag users may try wallabager in this case. I like to give a hint in the config file then:

```
# Site uses JavaScript, API-calls and/or techniques to prevent content catching, so...

# This works NOT with ftr.fivefilters.net (FTR|Fulltext-RSS)
# This works NOT with wallabag UI

# This only works with wallabagger browser-plugin with activated
# option 'Retrieve content from the browser' in it's settings
```
