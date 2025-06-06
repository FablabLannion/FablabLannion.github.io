---
author: colvert
tags: Actualité
imagefeature: https://static.fablab-lannion.org/WhereIsTheBeach2.png
layout: post
slug: whereisthebeach
date: 2014-02-15
title: "¿WhereIsTheBeach?"
comments: True
---
¿WhereIsTheBeach? est un projet qui vise à rendre tangible un ensemble de
données (météo, géo, web,..) pour rendre le choix d’une plage le plus
pertinent possible.

Supposons que l’été arrive (c’est audacieux comme postulat de départ – on vous
l’accorde -), vous avez fait le choix insensé et/ou courageux de découvrir le
Trégor, vous souhaitez soit aller faire une bronzette iodée, soit défier les
locaux sur votre planche à voile flambant neuve, soit tenter une action de
sociabilisation avec d’irréductibles gaulois.

Or vous ne connaissez pas trop la région, ¿WhereIsTheBeach? est fait pour
vous!

L’objet consiste en une carte munie d’un potentiomètre (sélecteur du critère)
de leds pour la représentation des plages (on a prévu une led rouge au cas où
la seule option soit de rester à la maison..) et un petit servomoteur pour
gérer une girouette. Le servo et le potentiomètre sont connectés à un arduino
équipé d’un shield ethernet. Sur détection de changement de critère (ou via un
timer) on déclenche l’envoi d’une requête à un web service, qui, en fonction
du critère nous renvoie la meilleure plage.

Pour la bronzette, on croise des données météos et géographiques et comme dit
le dicton « plage abritée sauve votre été ». Pour les sports nautiques, on se
base sur l’API windguru: « plage pour jiber sauve votre été ». Enfin pour la
plage la plus populaire d’un point de vue web, on utilise l’API twitter: «
plage pour geeker sauve votre été (ou pas) »

Via le sélecteur vous choisissez votre activité (bronzette, sport nautique,
popularité web), le système vous indique alors la meilleure plage via un
allumage de la led correspondant sur la carte. La direction est aussi pointée
par la girouette.

Plus d'information sur le WIki; <{{ site.url }}/wiki/index.php?title=Where_is_the_Beach%3F>

Le projet a été réalisé par Tangi, Pierre-Yves, Antoine et Morgan.

Plusieus axes d'amélioration sont possibles (joli support/carte/sélecteur,
plus de critères, plus de plages, bandes de led, mix avec aquamarium…).

Le projet a été soumis au projet Data+ et sera soumis au concours
Innov[@lannion]({{ site.url }}/membres/twitter_fablablannion/).


