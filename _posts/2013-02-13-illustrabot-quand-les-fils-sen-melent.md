---
author_gravatar: http://1.gravatar.com/avatar/1055c2d168d9878befb9c8810eda96dc?s=96&d=mm&r=g
author_fullname: Morgan Richomme
author: colvert
tags: arduino
feature: http://fablablannion.github.io/images/P1070203.jpg
layout: post
slug: illustrabot-quand-les-fils-sen-melent
date: 2013-02-13
title: "IllustraBot: quand les fils s&#8217;en mêlent"
comments: True
---
Hier fut un petit pas pour l'humanité mais un grand pas pour l'illustrabot.
L'horaire de fin des plus téméraires fut peu raisonnable mais a permis
d'avancer de manière significative. The nouvelle of the soirée est que tout
marche ..plus ou moins unitairement…y compris le robot!  

[![P1070207](http://fablablannion.github.io/images/P1070207-300x225.jpg)](http://fablab-
lannion.org/wp-content/uploads/2013/02/P1070207.jpg)Il y a encore du travail,
et pas qu'un peu, mais on peut noter quand même, non sans satisfaction que le
projet collaboratif est dans la bonne voie. De nouvelles têtes sont d'ailleurs
passées ce lundi, histoire de voir les barbus phosphorer: ils étaient donc
tous là ou presque: [@jerome](http://fablab-lannion.org/membres/jerome/) (chef
du pied à coulisse sous debian), @davidblaisonneau (sous chef sous mint),
[@fxp](http://fablab-lannion.org/membres/fxp/) (LTE, RPI et prévisions
météos), [@roozeec](http://fablab-lannion.org/membres/roozeec/) ,
[@jjacques](http://fablab-lannion.org/membres/jjacques/),
[@cebernard](http://fablab-lannion.org/membres/cebernard/) (android),
[@yann](http://fablab-lannion.org/membres/yann/) (expérimentateur de tête
d'illustrabot), @laurent (arduino SPI) @nicolaslenillon (arduino (grbl,
controle moteurs)), [@steph](http://fablab-lannion.org/membres/fanosteph/)
(version 2 axes (type CNC) du robot en bois), @cagnet (mécanique drawbot),
[@mathbreizh](http://fablab-lannion.org/membres/mathbreizh/) (châssis type
reprap), [@vbarreaud](http://fablab-lannion.org/membres/vbarreaud/),
[@guillaume.remy](http://fablab-lannion.org/membres/guillaume.remy/),
[@colvert](http://fablab-lannion.org/membres/colvert/) (lightbot)

Que les oubliés m'excusent et n'hésitent pas à faire connaître leur avatar..

[![fablab](http://fablablannion.github.io/images/fablab-200x300.jpg)](http://fablab-
lannion.org/wp-content/uploads/2013/02/fablab.jpg)

Mais revenons un peu sur le robot made in [@jerome](http://fablab-
lannion.org/membres/jerome/), "et en plus il
trace!".[![P1070205-1024x684-2](http://fablablannion.github.io/images/P1070205-1024x684-2-200x300.jpg)](http://fablab-
lannion.org/wp-content/uploads/2013/02/P1070205-1024x684-2.jpg) L'arduino
pilote 2 moteurs qui permettent de tracer des figures. Après un timide mais
régulier carré, Jérôme a osé le cube, promesse d'arabesques printanières.
[@yann](http://fablab-lannion.org/membres/yann/) a tenté quant à lui des trucs
au niveau du support de crayon: choix de la pièce, lestage du tout, placement
du crayon…beaucoup d'empirisme qui alimenteront n'en doutons pas les débats
sur l'optimisation du porte crayon.

L'équipe android finalisait l'integration de gestures et générait des rampes
de gcode.

Pendant que Jérôme traçait des Z, [@david.blaisonneau](http://fablab-
lannion.org/membres/david.blaisonneau/) chevauchait tornado - le serveur
websocket - et s'improvisait une petite remise à niveau python…après quelques
péripéties JQuery, mise à l'echelle, cast et arrondis, le serveur était en
mesure de transmettre le GCode à l'arduino.

[@fxp](http://fablab-lannion.org/membres/fxp/) y allait de son fluide (et du
soutien des bell labs) pour faire en sorte que RPi et LTE s'apprivoisent.

A l'aurore, [@Laurent](http://fablab-lannion.org/membres/laurent/) faisait un
petit bilan, il indiquait le début d'intégration du code SPI + Grbl dans un
même projet, la mise en place de l'outil de développement pour l'Arduino et le
début de mapping avec les drivers des moteurs et l'Arduino.

A quelques pas de là, [@guillaume.remy](http://fablab-
lannion.org/membres/guillaume.remy/) faisait ses premiers tests du lightbot.
L'autopilote du drône est en fait assez simple; Il référence des points
(X,Y,Z) dans un fichier de configuration. Il est donc possible via les points
transmis dans le GCode d'élaborer la route du drône dans un plan vertical.
Dans un premier temps il a commandé au drône le traçage (et donc l'allumage de
led) d'une droite de 2m à 1m du sol.

Opération réussie, on voit la trace des leds grâce à la pause longue de
l'appareil photo

[![IMG_0153](http://fablablannion.github.io/images/IMG_0153-300x200.png)](http://fablab-
lannion.org/wp-content/uploads/2013/02/IMG_0153.png)

mais il va falloir ruser, le drone utilise sa caméra pour se caller et a donc
besoin de voir le sol, or l'effet est plus saisisant à faible
luminosité…..bref il va falloir trouver un compromis, des discussions sont
lancées…



à suivre….


