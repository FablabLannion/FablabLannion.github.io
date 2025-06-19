fil---
layout: page
permalink: /animations/
title: A Propos
description: "Nos animations"
imagefeature: fourseasons.jpg
chart: true
---



{% assign total_words = 0 %}
{% assign total_readtime = 0 %}
{% assign featuredcount = 0 %}
{% assign statuscount = 0 %}

{% for post in site.posts %}
    {% assign post_words = post.content | strip_html | number_of_words %}
    {% assign readtime = post_words | append: '.0' | divided_by:200 %}
    {% assign total_words = total_words | plus: post_words %}
    {% assign total_readtime = total_readtime | plus: readtime %}
    {% if post.featured %}
    {% assign featuredcount = featuredcount | plus: 1 %}
    {% endif %}
{% endfor %}




Attention, cette page est en construction !
=============


Nos animations
--------------

VOus trouvez ici les fiches ateliers des différentes animations que nous proposons, au fablab ou à l'extèrieur.
La liste présentée ici ne sera pas exaustive.
VOus avez un projet? une idée? Vous souhaitez un devis? Contactez-nous !



