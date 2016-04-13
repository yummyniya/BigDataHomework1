# BigDataHomework1
## Overview  
* Colleting Data Tool
* Data Source
* Keywords

## Collecting Data Tool
Using [Logstash](https://www.elastic.co/products/logstash) (https://www.elastic.co/products/logstash) from Elastic.  
Setup config with two plugins: input and output  
## Data Source  
Input: **Twitter API** Data  
Output: **JSON** format  
Data Format: full tweets  
Example:

    "_index": "twitter",
    "_type": "logs",
    "_id": "AVP5GvBMbnn9b7UgnezV",
    "_version": 1,
    "_score": 1,
    "_source": {
        "created_at": "Sat Apr 09 03:40:01 +0000 2016",
        "id": 718644610361208800,
        "id_str": "718644610361208833",
        "text": "@D0wJ0nEs is that a guy from Catfish? I'm just now remembering.",
        "source": "<a href="http://twitter.com/download/iphone" rel="nofollow">Twitter for iPhone</a>",
        "truncated": false,
        "in_reply_to_status_id": 718644394736422900,
        "in_reply_to_status_id_str": "718644394736422912",
        "in_reply_to_user_id": 103335732,
        "in_reply_to_user_id_str": "103335732",
        "in_reply_to_screen_name": "D0wJ0nEs",
        "user": {
            "id": 217630894,
            "id_str": "217630894",
            "name": "Ramon",
            "screen_name": "LowKei_",
            "location": null,
            "url": null,
            "description": "Mind of Mine.",
            "protected": false,
            "verified": false,
            "followers_count": 6171,
            "friends_count": 990,
            "listed_count": 40,
            "favourites_count": 1198,
            "statuses_count": 228993,
            "created_at": "Sat Nov 20 01:57:34 +0000 2010",
            "utc_offset": -18000,
            "time_zone": "Central Time (US & Canada)",
            "geo_enabled": false,
            "lang": "en",
            "contributors_enabled": false,
            "is_translator": false,
            "profile_background_color": "8A1A1A",
            "profile_background_image_url": "http://pbs.twimg.com/profile_background_images/680646659861168128/94_RDh2E.jpg",
            "profile_background_image_url_https": "https://pbs.twimg.com/profile_background_images/680646659861168128/94_RDh2E.jpg",
            "profile_background_tile": true,
            "profile_link_color": "BF0B0B",
            "profile_sidebar_border_color": "FFFFFF",
            "profile_sidebar_fill_color": "000000",
            "profile_text_color": "736F6F",
            "profile_use_background_image": true,
            "profile_image_url": "http://pbs.twimg.com/profile_images/697440990685081600/RLGrzLM-_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/697440990685081600/RLGrzLM-_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/217630894/1459438967",
            "default_profile": false,
            "default_profile_image": false,
            "following": null,
            "follow_request_sent": null,
            "notifications": null
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 0,
        "favorite_count": 0,
        "entities": {
            "hashtags": [ ],
            "urls": [ ],
            "user_mentions": [
                {
                    "screen_name": "D0wJ0nEs",
                    "name": "Mr. GoodTweet",
                    "id": 103335732,
                    "id_str": "103335732",
                    "indices": [
                        0
                        ,
                        9
                    ]
                }
            ],
            "symbols": [ ]
        },
        "favorited": false,
        "retweeted": false,
        "filter_level": "low",
        "lang": "en",
        "timestamp_ms": "1460173201538",
        "@version": "1",
        "@timestamp": "2016-04-09T03:40:01.000Z"
    }
## Keywords
1.  obama
2.  trump
3.  donald trump
4.  realDonaldTrump  
The reason I chose these keywords is I'm curious about why Donald Trump is getting more supported by US people. Too see if any connection between US President Obama and Trump. Also, I want to see whether those tweets are more likely positive or not.
