---
layout: post
title: About
permalink: /about/
img: WeddingPrep.jpg
---

Edmonds Bakery is right in the heart of downtown Edmonds and has been right here since 1927. The current owner, Ken Bellingham, purchased the bakery in 1993 but has been baking here in Edmonds since 1977. All that time he has been making beautiful cakes, doughnuts and pastries. The ovens fire up every Tuesday through Saturday and  doors are open from 7 am to 4:30 pm. Come in to enjoy a small business's contribution to the vibrant and closenit community of Edmonds.

{% assign today = site.time | date: '%w' %}
{% case today %}
   {% when '0' %}

   {% when '1' %}
   <h1>Mon</h1>
    {% when '2' %}
        <h1>Tue</h1>
    {% when '3' %}
        <h1>Wed</h1>
    {% when '4' %}
        <h1>Thu</h1>
    {% when '5' %}
        <h1>Fri</h1>
    {% when '6' %}
        <h1>Sat</h1>
{% endcase %}
<!-- <iframe class="video" src="https://www.youtube.com/embed/SQ8U7M-YZbM" frameborder="0" allowfullscreen></iframe> -->