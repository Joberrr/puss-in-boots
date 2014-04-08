---
layout: page
title: Ciao mondo!
tagline: Kitty? You are not as good as they say. You are better!
---
{% include JB/setup %}

## Puss in Boots

[La Chat Botte](http://en.wikipedia.org/wiki/Puss_in_Boots) is a fairy tale about a cat written by Giovanni Francesco Straparola.

This website is a place for me to practice my [Jekyll](http://jekyllrb.com/) wizardry.

Yes, you should be amazed by such skills! ;-)


### Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

1. Get used to writing [mark down](http://daringfireball.net/projects/markdown/syntax)
2. Put a new banner up the top.  See a banner?  No not yet? ok.
3. Post about this site on [my twitter feed @ joberrr](http://twitter.com/joberrr).  Don't see that yet either?
4. Re-connect the comments on this site, setup intensedebate account.
5. Add more stuff to my to do list.
