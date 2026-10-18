---
author: colvert
tags: Actualité
imagefeature: https://static.fablab-lannion.org/800px-Bzzz-logo_fond_blanc.jpg
layout: post
slug: bzzz-breaking-news-la-nuit-y-a-moins-de-lumiere
date: 2013-05-23
title: "Bzzz: breaking news &#8211; la nuit y a moins de lumière!"
comments: True
---
Dans le cadre du projet Bzzz, nous avons voulu tester la chaîne d'intégration:

capteur ===== Arduino ===== Shield GSM ===== Application backend

Nos experts du piston à pression et de la bouteille de soda au glycol étant
fort affairés, nous avons utilisé un simple capteur de luminosité. L'arduino
alimenté par USB remontait l'information du capteur à intervalle régulier
(toutes les 4 minutes = taille max) au système via SMS comme décrit dans le
wiki. Le but était d'éteindre de façon logicielle le shield GSM entre 2 envois
afin de faire des économies d'énergie.

Et du coup nous avons obtenu une jolie courbe

[![Screenshot from 2013-05-23
12:37:04](https://static.fablab-lannion.org/Screenshot-
from-2013-05-23-123704.png)](https://static.fablab-lannion.org/Screenshot-
from-2013-05-23-123704.png)

Ce petit test a permis de montrer la limite de l'endormissement logiciel du
shield GSM à 4 minutes, du coup David a dû modifier la librairie pour faire
"dormir" le shield GSM un peu plus longtemps.

Il a également démontré de manière très nette que le jour il fait jour et que
la nuit….il fait nuit…même pendant l'été austral breton

Pour le prochain test, nous allons débrancher l'USB et nous en remettre à une
batterie et un petit panneau solaire histoire de voire comment ça se comporte
électriquement et autonomiquement parlant…  
En attendant d'intégrer les vrais capteurs, de remonter la source Zigbee voire
de s'insérer dans le réseau de capteurs
[sensonet](https://projects.emerginov.org/sensonet/)…  
à suivre….




