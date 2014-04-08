---
layout: page
title: Bonjour tout le monde!
tagline: Kitty? You are not as good as they say. You are better!
---
{% include JB/setup %}

## Puss in Boots

[La Chat Botte](http://en.wikipedia.org/wiki/Puss_in_Boots) is a fairy tale about a cat written by Giovanni Francesco Straparola.

This website is a place for me to gather code snippets to allow me to practice my [Jekyll](http://jekyllrb.com/) wizardry.

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
3. Post about this site on my twitter feed.  Don't see that yet either?
4. Re-connect the comments on this site, setup DISCUS account.
5. Add most stuff to my to do list.
