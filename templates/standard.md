```yml
#http_header(User-Agent): Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:140.0) Gecko/20100101 Firefox/140.0
#http_header(user-agent): Mozilla/5.0 (Macintosh; Intel Mac OS X 14.7; rv:140.0) Gecko/20100101 Firefox/140.0
#http_header(User-Agent): Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)
#http_header(User-Agent): Mozilla/5.0 (compatible; Yahoo! Slurp; http://help.yahoo.com/help/us/ysearch/slurp)
#http_header(User-Agent): Mozilla/5.0 (compatible; bingbot/2.0; +http://www.bing.com/bingbot.htm)
#http_header(User-Agent): curl/7.83.1
#http_header(User-Agent): curl/7.54.0
#http_header(User-Agent): PHP/8.4
#http_header(User-Agent): PHP/7.4
#http_header(User-Agent): Mastodon/4.3.2 (http.rb/5.2.0; +https://mastodon.social/)
#http_header(User-Agent): Mastodon/4.3.2 (http.rb/5.2.0; +https://mastodon.social/) Bot

#http_header(referer): https://google.com
#http_header(cookie): key=value

## just for testing, to get sure, wallabag also get's the lead image.
insert_detected_image: no 

#body: //article[1]
#body: //div[contains(concat(' ',normalize-space(@class),' '),' item ')]
#title: //meta[@property='og:title']/@content
#author: //meta[@name='author']/@content
#date: //time/@datetime
#date: substring-before(substring-after(//script[@type="application/ld+json"], '"datePublished":"'), '","dateModified"')


#strip_attr: //h2[contains(@class,'wp-block-heading')]/@class
#strip_attr: //h3[contains(@class,'wp-block-heading')]/@class

## [wallabag] prevent indentation. only one of these lines:
#strip_attr: //div[contains(@class, 'container')]/@class
#replace_string(class="container): class="foo-cntnr

#skip_json_ld: yes
#prune: no
#tidy: no

test_url: 
```
