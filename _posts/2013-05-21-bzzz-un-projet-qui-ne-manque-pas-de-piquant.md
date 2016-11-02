---
author_gravatar: http://1.gravatar.com/avatar/1055c2d168d9878befb9c8810eda96dc?s=96&d=mm&r=g
author_fullname: Morgan Richomme
author: colvert
tags: []
feature: http://fablablannion.github.io/images/800px-Bzzz-logo_fond_blanc.jpg
layout: post
slug: bzzz-un-projet-qui-ne-manque-pas-de-piquant
date: 2013-05-21
title: "Bzzz un projet qui ne manque pas de piquant"
comments: True
---
Depuis quelques semaines, un nouveau projet a débuté au Fablab: Bzzz.

Il s'agit d'un projet de suivi de ruches pour une apiculture vraiment Zen
(pour l'apiculteur et pour ses abeilles ^^). Le but de ce projet est donc de
proposer gratuitement à tout apiculteur amateur un peu bricoleur les plans
d'un kit de suivi des ruches.

on peut résumer tout ça sous le schéma suivant:

[![Bzzz](http://fablablannion.github.io/images/Bzzz-1024x599.png)](http://fablab-
lannion.org/wp-content/uploads/2013/05/Bzzz.png)

Comme pour l'Illustrabot, le projet nécessite l'intégration de divers éléments
et des compétences variées:

  * un capteur permettant de mesurer la masse des ruches (balance, jauge de contrainte, piston à pression, ..)
  * un système de communication sans fil entre N ruches (arduinos avec module Zigbee) et 1 ruche maître (arduino avec un module Zigbee et un module GSM)
  * un système de communication entre la ruche maître et le nuage basé sur GSM
  * un solution qui stocke les données, graphe les résultats et emet des alarmes (si delta masse &gt; 2Kg) par SMS, mail ou via appel.

on doit prendre en compte le fait que le système doit supporter les conditions
climatiques et être autonome électriquement.

A suivre…

Plus d'infos sur http://fablab-
lannion.org/wiki/index.php?title=Suivi_des_ruches


