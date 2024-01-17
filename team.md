---
layout: page
title: Team
---

<div  class="posts">
{% for post in site.team %}
<article style="text-align: center; width: 10%; min-width: 100px;">
            <a href="{{ post.url  | absolute_url }}" class="image">
                <picture>
                <img src="{{ post.image | absolute_url }}" alt="{{ post.image-alt }}" style="border-radius: 50%; width: 100%;"  />
                </picture> 
                <p style="margin-top: -80px; padding-top: 0px; color: #444444;">
                <a style="color: black; font-weight: 400; text-decoration: none;" href="{{ post.url  | absolute_url }}">{{ post.name }}</a> <br/>
                {{ post.description }}</p>
            </a>
        </article>
  {% endfor %}
</div>  
