search-politicians
===

# Idea

Forgive but never forget.

https://vote.ly.g0v.tw/

# Target Scope

https://zh.wikipedia.org/wiki/2018年中華民國直轄市長及縣市長選舉

# User Stories

1. As a voter, I want to view the list of news of each candidates through a webpage portal so that I can easily understand what has the candidate done in the past few years.
2. As a voter, I want to narrow the search time with filter so that I can view data within a selected range (like 4 years).

# Posible material

- News
  - Google news
  - Yahoo news
- Google search results
- Websites of main stream news
  - The facebook comment of news
- Youtube
- Facebook public posts

# News

https://news.google.com.tw/

https://tw.news.yahoo.com/
https://developer.yahoo.com/boss/search/boss_api_guide/

https://www.msn.com/zh-tw/news

https://udn.com/news/index

http://www.ltn.com.tw/

http://www.chinatimes.com

https://www.ettoday.net

https://news.tvbs.com.tw/

https://news.ebc.net.tw/

https://www.epochtimes.com

http://www.storm.mg

http://news.pchome.com.tw/

http://pnn.pts.org.tw/

https://tw.appledaily.com/

https://news.ftv.com.tw/

# Youtube

- Video talk more than news
- Title/description only will not show the public opinion
  - Some video disable comments.
- Data depends on how popular a candidate is.

https://www.youtube.com/yt/dev/zh-TW/api-resources.html

# Facebook

- Only public posts
- Can collect reactions from public users.

https://developers.facebook.com/docs/graph-api/using-graph-api

https://graph.facebook.com/820882001277849?access_token=
```
{
   "error": {
      "message": "(#10) To use 'Page Public Content Access', your use of this endpoint must be reviewed and approved by Facebook. To submit this 'Page Public Content Access' feature for review please read our documentation on reviewable features: https://developers.facebook.com/docs/apps/review.",
      "type": "OAuthException",
      "code": 10,
      "fbtrace_id": ""
   }
}
```
- [ ] Create a facebook app.
  - [ ] Must be reviewed.

