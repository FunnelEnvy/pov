---

title: Use cookies, not JavaScript, to set custom User IDs
feed: show
date: 2022-10-21
categories: ["Measurement"]
# permalink: /credits
# format: list

---

If you're going to create a custom user id to identify visitors then we recommend setting this as a HTTP response cookie, instead of via Javascript. 

The reason for sending this in the HTTP response from the server instead of setting via Javascript is because of ITP, which impacts all Safari (incl iOS) browsers. [ITP will sandbox all Javascript set cookies to 7 days](https://clearcode.cc/blog/intelligent-tracking-prevention-faq/#ITP-restrictions), which would impact your ability to track users on those browsers over a longer period of time.

The current version of ITP (2.3) does not yet impose restrictions on HTTP cookies.