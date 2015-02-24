---
author: manasgarg
comments: true
date: 2008-09-19 08:01:00+00:00
layout: post
slug: web-within-web-where-one-size-fits-all-%e2%80%9cweb-search%e2%80%9d-doesn%e2%80%99t-fit
title: 'Web Within Web : Where one-size-fits-all “Web Search” doesn’t fit!'
wordpress_id: 67
---

[First [published](http://www.pluggd.in/technology/web-within-web-where-one-size-fits-all-search-doesnt-fit-2707) at [pluggd.in](http://pluggd.in).]_  
  
Search is not an application. It is not a feature. It is a _[_navigation method_](http://www.pluggd.in/2008/09/does-search-solves-more-intent-than-navigational-sites). It is a must-have for any website.

Fortunately, for most of the websites, Google is there so they don't have to do their own search. That's why [mysql.com](http://mysql.com/) doesn't have to do search. Google does it for [mysql.com](http://mysql.com/). _But Google's one-size-fits-all doesn't really fit all_. SlideShare cannot rely on Google search. Flickr cannot rely on Google search. They have to do their own search. Flight booking portal cannot rely on Google search. It has to do its own search of flight availability.

Now we are getting into an interesting area. We are talking about _what Google search cannot do_.

But before I dive deeper into what Google search cannot do, I must lay down the yard-stick for measuring success in doing search. Since, search is primarily a navigation thing and navigation is done best when it is almost invisible to people, search is done best when people don't realize that they are doing search.  
It just flows. I search, I get the definite winner among the top results, I don't even register that I searched. However, search is bad when I realize that I am searching. If I want to know the best restaurants in Bangalore, and I search it on Google, what do I get? Is there a definite winner? No. So, Google search has failed.

**So, where all Google search fails?** Several places. In fact, it's amazing that Google search fails at so many places. And it's even more amazing that the number of such places is increasing. Let's look at some broad categories -

**1. A rather closed cluster of information.** Google search is based on popularity of a page across the web for given keywords. But consider Slideshare. It's a small web within the world wide web. Consider scribd. Consider video sharing sites. Consider social networks. Consider friendfeed. Consider twitter. The rules that determine the popularity of some content at these places are different. On slideshare, it matters how many times a PPT was viewed, how many comments it has, how many users saw it through the end and how many left it in between. It has its own mechanism by which the popularity for a PPT can be determined. Search for "website scalability" on Google and Slideshare and compare the quality of results. Twitter? Isn't a lot of interesting stuff happening there? Can Google mine it the way it mines general web pages? The rules for ranking are different.

So, Google search fails (well, mostly ![;)](http://www.pluggd.in/wp-includes/images/smilies/icon_wink.gif) when it comes to a web within the web.

![](http://www.irony.com/images/article%20images/worldwidewebcity.jpg)

**2. Not everything on the web is a webpage.** And Google's one-size-fits-all doesn't work for non-webpages. That's why Google has several other specific search implementations - Images, Code, Groups, Blogs etc. And there are many that are yet to come - Word documents, PDF, PPT, microblogs, blog comments and what not. I can go on but you got the idea. Right? While Google is a clear winner for webpages but there are several other things which are not webpages, which need to be searched on the web and Google either doesn't search it or doesn't search it with equal maturity. What's even more interesting is that you'll find overlap in point #2 and point #1. A lot of things on the web which are not webpages are found in closed clusters which will have their own custom method for ranking.

**3. There is also data on the web.** List of available flights from Delhi to Mumbai, their price, airline name, airline number, available seat details, timings etc is data. It is not a webpage or something like PDF which can be just displayed. This is data and it can be shown in interesting ways and it can be used in interesting ways. Same goes with the hotels. List of hotels in a city and various attributes of those hotels like location, room sizes, ambience, facilities etc. If you are wondering what search has to do with all this data, let me remind - search is a navigation method. When I am going to a new city and I want to decide which hotel to stay in, my decision is based on various such parameters.

But Google search doesn't work here. And it will not. The purpose is different. Google search is for heading to a page whose URL I don't know but I know some keywords pertaining to that page. It is not for viewing the data.

**4. Search as an integral component of a service.** I would have taken trip planner example for this i.e. booking a flight for a city, booking the cab, the hotel, deciding the sight-seeing etc. But since that's already widely talked about, I'll take something else. Just to prove the wide applicability of search and how we need to see search in a different perspective.

Let's talk about [phulki.com](http://www.pluggd.in/2008/07/meta-aggregator-indian-music-sites-phulki). It's a search engine for desi music. Its interface looks very much like Google search. But is that how it should be? No. I go to Google to navigate to the final destination page. Go to Google, search for "mysql linux download". Click on the top result and go to [mysql.com](http://mysql.com/) page. But I go to [phulki.com](http://phulki.com/) for listening to the music online or for downloading it. The purpose is different. If I search for "Maula mere le le meri jaan", I don't want 10 results showing me the same song from different sources. I don't care which source it comes from. I just want the best listening/downloading experience. So, show it to me as one song with a drop-down list of various sources (the supposedly best one auto-selected) and a download link (yes, just a single download link) and again a drop down list of sources for download.

If I search for "chak de india", it should figure out that it's an album and show me a list of songs from that movie, nicely ordered with an option to put all songs of that movie in my playlist with a single click.

And how about "Those who listened to Maula-mere-le-le-meri-jaan also listened to ek-parinda-aisa-toota"?

It will have technical challenges. It will require phulki to index differently. _But phulki is not a search engine for desi music! It is a website for playing desi music!! Search being just the navigation model to reach the music that I want._

Take local search for example. When I search for electronic appliance shop in Pune Camp area, I want not only the name/phone/address, I would also like to be shown the reviews people have left for those shops on different sites.

**Summary**

There are a lot of contexts in which general purpose, "web search" as provided by Google and others doesn't work (at least not with as much maturity). And it's interesting to note that such contexts are growing. The number of sites which are web-within-the-web are increasing. More and more non-webpages are making appearance on the web. Web based applications have started bringing in data (hotels in a city is data, not a webpage; let's accept this). And finally, there are several web based applications coming up (like phulki, local search) where search is an integral part of their workflow.

These trends spell an interesting future for search but that's a topic for another article some other time.
