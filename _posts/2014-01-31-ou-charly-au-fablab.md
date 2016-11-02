---
author_gravatar: http://0.gravatar.com/avatar/6a767bcd26d052496dac0f142243cb82?s=96&d=mm&r=g
author_fullname: Nicolas Guédon
author: pofexpray
tags: Machines
feature: https://static.fablab-lannion.org/DSC_0059.jpg
layout: post
slug: ou-charly-au-fablab
date: 2014-01-31
title: "Mais où est Charly ? &#8230; au FabLab"
comments: True
---
[![Premier Fraisage
CharlyRobot](https://static.fablab-lannion.org/DSC_0059-300x168.jpg)](http://fablab-
lannion.org/wp-content/uploads/2014/01/DSC_0059.jpg)

Ne vous y trompez pas, Charly ce n'est pas le barbu fier de tenir une planche
gravée d'un logo banal mais bel et bien la machine grise en arrière-plan. Le
nom complet de cette machine est la [CharlyRobot](http://fablab-
lannion.org/wiki/index.php?title=CharlyRobot) et vous la trouverez maintenant
au FabLab de Lannion.

Le barbu en question ([@theo](http://fablab-lannion.org/membres/theo/)) et les
autres acteurs de cette réhabilitation ([@david](http://fablab-
lannion.org/membres/david.blaisonneau/), [@tangi](http://fablab-
lannion.org/membres/tangi/), [@pofexpray](http://fablab-
lannion.org/membres/pofexpray/)) sont fiers d'annoncer que la CharlyRobot du
FabLab de Lannion, une fraiseuse de table précise, est maintenant
fonctionnelle et vient de travailler sur son tout premier objet (gravure sur
verre). La CharlyRobot ne se limitera pas à de la gravure et il reste encore
du travail pour la faire évoluer, mais on atteint déjà une qualité de gravure
satisfaisante (sans réglage particulier et sans fraise adaptée).

[![DSC_0069\[1\]](https://static.fablab-lannion.org/DSC_00691-300x168.jpg)](http://fablab-
lannion.org/wp-content/uploads/2014/01/DSC_00691.jpg)

Mais avant d'en arriver là, il a fallu de la patience et… de la patience (et
aussi… de la patience).

La CharlyRobot est arrivée au FabLab en Septembre 2013. Au début ce n'était
qu'un châssis et des moteurs, aucune documentation et aucune carte
électronique. Comment la piloter ? Comment l'alimenter ? Les moteurs sont-ils
encore en état ? Par où commencer ? Qui est volontaire pour la remettre en
route ? Beaucoup de questions sont arrivées en même temps que le châssis.

[![vlcsnap-2013-10-04-22h21m48s240](https://static.fablab-lannion.org/vlcsnap-2013-10-04-22h21m48s240-300x168.png)](http://fablab-
lannion.org/wp-content/uploads/2013/10/vlcsnap-2013-10-04-22h21m48s240.png)

Il a fallu dans un premier temps alimenter les 3 servomoteurs (en 12v sur la
vidéo puis ensuite en 24v pour une vélocité accrue):





Mais une fois alimentée, il restait encore l'électronique et le pilotage par
ordinateur des 3 axes a réaliser :

  * Une carte prototype a été conçue pour valider le schéma d'électronique de puissance pour chaque moteur.
  * LinuxCNC a été installé et configuré pour envoyer les données via port Parallèle à la carte électronique.

Il a déjà fallu plusieurs phases de test de la carte électronique, de
débogage, de réglage de LinuxCNC pour avoir un premier résultat sur 1 axe :

Puis sur 2 axes:

Le schéma étant validé pour 2 axes, il était alors temps de passer sur une
carte électronique finale ([FaisTonPCB](http://fablab-
lannion.org/wiki/index.php?title=FaisTonPCB)) gérant 3 axes.

[![DSC_0062](https://static.fablab-lannion.org/DSC_0062-300x168.jpg)](http://fablab-
lannion.org/wp-content/uploads/2014/01/DSC_0062.jpg)

Après réalisation de la carte et quelques réglages (ajout de ports parallèle
sur le PC de commande notamment), il était temps de relever le défi de
réaliser un premier fraisage via le matériel disponible pour le moment
(impatience oblige !). Mais il fallait avant tout un support adapté à l’outil
de type Dremel:

[![DSC_0061](https://static.fablab-lannion.org/DSC_0061-e1390838256564-168x300.jpg)](http://fablab-
lannion.org/wp-content/uploads/2014/01/DSC_0061-e1390838256564.jpg)

L'heure de vérité arrive alors pour la CharlyRobot (gravage du logo par défaut
inclus dans LinuxCNC) !!!

Charly est maintenant fonctionnelle au FabLab et elle va continuer à évoluer :

  * Table aspirante (maintien des pièces à fraiser)
  * Meilleur support pour l'outil de type Dremel
  * Capot de protection pour la sécurité
  * Arrêt d'urgence pour la sécurité
  * Support et Mise en place d'une défonceuse sur la Charly (gros fraisage)
  * Et bien plus encore…

[![DSC_0057](https://static.fablab-lannion.org/DSC_0057-e1390839539192-168x300.jpg)](http://fablab-
lannion.org/wp-content/uploads/2014/01/DSC_0057-e1390839539192.jpg)

Une fierté affichée

Cette histoire vous a plus et vous voulez devenir acteur du FabLab ? Avoir la
fierté de redonner vie à une machine, concrétiser un projet, une idée ?
N'hésitez pas à venir nous rejoindre !

En attendant suivez-nous sur
[facebook](https://www.facebook.com/fablablannion) et
#[twitter](https://twitter.com/fablablannion):

A bientôt


