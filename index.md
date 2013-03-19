---
layout: page
---
{% include JB/setup %}

<intro>Hi, I'm Timoni West, a web + mobile designer in Brooklyn, New York.  I currently work at [Foursquare](http://www.foursquare.com).  Before that, I worked at [Flickr](http://www.flickr.com/), and [Scribd](www.scribd.com). I've also done work with amazing startups around the country, including [Lift](http://lift.do/), [Bitly](http://bitly.com), [Airtime](http://www.airtime.com/), and [Causes](http://www.causes.com/).</intro>

I'm most proud of [Recollect](http://recollect.com), which I made with [Chris Martin](http://about.me/cjmartin) and [Bertram Fan](http://thatsaspicymeatball.com/).
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

