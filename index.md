---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: post
excerpt_separator: <!--more-->
---

{% for post in site.posts %}
<li style="list-style-type:none;"><a class="post-title" href="{{post.permalink}}">{{post.title}}</a>
<p>{{post.excerpt}}</p></li>
{% endfor %}