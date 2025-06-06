---
layout: page
permalink: /about/
title: A Propos
description: "A Propos"
imagefeature: fourseasons.jpg
chart: true
---

<figure>
  <img src="{{ site.url }}/images/logoSeul-300x300.jpg" alt="FabLab Lannion">
  <figcaption>FabLab Lannion</figcaption>
</figure>

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


Nous soutenir
=============

Adhérer
-------

Le moyen le plus simple est déjà adhérer à l’association. Vous trouverez toutes les informations sur la
[page dédiée](https://wiki.fablab-lannion.org//index.php?title=Adh%C3%A9sion).
Nous faire don de matériel informatique, électronique ou de fabrication numérique en fin de vie

Vous renouvelez votre parc informatique ou électronique, ou votre matériel de fabrication numérique ? Plutôt que d’acheminer ce matériel vers une filière de recyclage où il sera détruit alors qu’ils est encore en état de fonctionnement, vous pouvez nous les proposer afin que nous leur donnions une seconde vie. Nous assurons l’effacement des données éventuellement situées sur les disques des ordinateurs, et proposons ensuite ce matériel à prix préférentiel à des publics concernés par la fracture numérique.

Nous sommes titulaires du label Ordi2.0, aussi votre entreprise pourra à son tour solliciter le label Ordi2.0 en tant que Donateur, et l’exploiter dans le cadre de la communication sur la RSE (Responsabilité Sociale d’Entreprise).

Vous envisagez de nous donner du matériel ? Vous avez des questions ? Contactez-nous…

Devenir mécène
--------------

Afin de financer les investissements significatifs nécessaires à la mise en place d’un atelier polyvalent, le fablab de Lannion a organisé plusieurs opérations de financement participatif. ces campagnes ont permis de compléter les fonds publics obtenus, et de couvrir la part légale d’autofinancement. On leur doit notamment l’acquisition de notre première imprimante 3D et de notre découpeuse LASER. Vous pouvez à tout moment nous aider! En effet le plan d’investissement machine prévoit l’acquisition ou le renouvellement de machines de façon régulière. Vos dons serviront à enrichir le parc de machines.

Les entreprises mécènes verront leur image associée durablement au fablab. Le fablab pourra participer à des opérations de communication conjointe et référencera votre entreprise comme partenaire du fablab, et inclura ainsi votre logo dans ses supports de communication.

Vous envisagez de nous aider financièrement ? Vous avez des questions ? Contactez-nous…

Informations administratives
============================

L'association a été crée en Décembre 2012 et est déclarée auprès de la sous-préfecture de Lannion

* [Statuts](https://wiki.fablab-lannion.org//index.php?title=Statuts)
* numéro RNA : W223001420 [Récépissé de déclaration](https://static.fablab-lannion.org//Recepisse_CR.pdf)
* Parution au JO le 22/12/2012 [Annonce](https://www.journal-officiel.gouv.fr/pages/associations-detail-annonce/?q.id=id:201200510384)
* numéro SIREN : 789 912 854

Informations sur le site
========================

Ce site est celui du **FabLab de Lannion**, porté par l'association loi 1901 Kernel.

Il y a aujourd'hui {{ site.posts | size }} posts dans {{ site.categories | size }} categories contenants {{ total_words }} mots, qui prendront, pour un lecteur moyen ({{ site.wpm }} WPM) environ <span class="time">{{ total_readtime }}</span> minutes a lire.

{% if featuredcount != 0 %}Il y a <a href="{{ site.url }}/featured">{{ featuredcount }} article de qualité</a>, a lire absolument!{% endif %}

L'article le plus récent est {% for post in site.posts limit:1 %}{% if post.description %}<a href="{{ site.url }}{{ post.url }}" title="{{ post.description }}">"{{ post.title }}"</a>{% else %}<a href="{{ site.url }}{{ post.url }}" title="{{ post.description }}" title="Read more about {{ post.title }}">"{{ post.title }}"</a>{% endif %}{% endfor %} publié le {% for post in site.posts limit:1 %}{% assign modifiedtime = post.modified | date: "%Y%m%d" %}{% assign posttime = post.date | date: "%Y%m%d" %}<time datetime="{{ post.date | date_to_xmlschema }}" class="post-time">{{ post.date | date: "%d %b %Y" }}</time>{% if post.modified %}{% if modifiedtime != posttime %} et modifié le <time datetime="{{ post.modified | date: "%Y-%m-%d" }}" itemprop="dateModified">{{ post.modified | date: "%d %b %Y" }}</time>{% endif %}{% endif %}{% endfor %}.

La dernière modification a été faite le {{ site.time | date: "%A, %d %b %Y" }} à {{ site.time | date: "%I:%M %p" }} [UTC](https://en.wikipedia.org/wiki/Coordinated_Universal_Time "Temps Universel Coordonné").




