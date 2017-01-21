---
inFeed: true
description: >-
  There were over 46 issues on this page alone last time I looked -
  https://validator.w3.org
dateModified: '2017-01-21T17:59:47.174Z'
datePublished: '2017-01-21T17:59:47.732Z'
title: What's wrong with this thegrid.io generated site?
author: []
publisher: {}
via: {}
sourcePath: _posts/2017-01-21-whats-wrong-with-this-thegridio-generated-site.md
starred: false
datePublishedOriginal: '2017-01-21T17:59:47.732Z'
_type: Blurb

---
# What's wrong with this thegrid.io generated site?

## The markup generated does not pass The W3C Markup Validation Service!

There were over 46 issues on this page alone last time I looked - [https://validator.w3.org][0]
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/41ec83a2-8e8e-4c44-b28b-535688ba8830.png)

## The assets are not hosted with the site.

The assets are scattered over at least 5 locations.

The site suffers from increased latency and can't benefit from recent enhancements like http2\.

* https://ajax.googleapis.com
* https://cdnjs.cloudflare.com
* https://cdn.thegrid.io
* https://the-grid-user-content.s3-us-west-2.amazonaws.com
* https://imgflo.herokuapp.com

To add to the latency, many of the assets are not minified / compressed and currently make up around 20% of the requests.

## This site has minimal content and yet the page source alone is 595KB!

If you add all the assets on the page you end up with a total size of 63.3MB. Try rendering that on a mobile with 3 bars of connection.

## There is currently no way to add a cookie banner to comply with EU cookie law

Region specific but still something you need to consider.

## It's just too slow

Like 10 seconds page load slow. Of course if the above items were fixed things would be much improved.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/2f63ff9d-3c0f-4ffe-959d-582142d42125.png)

## Support took over 24Hrs to respond

If you have an issue with your site you dont want to be waiting 24Hrs before you get a response.

I initially raised the issue with thegrid.io support but have yet to get a response.

## The image processing is still flawed

Take a look at the logo at the top of the page. You can't see the text right? That's because the colors chosen by the AI did not take into account the images on the page.

[0]: https://validator.w3.org/nu/?doc=https%3A%2F%2Fwave2.org%2F "https://validator.w3.org"