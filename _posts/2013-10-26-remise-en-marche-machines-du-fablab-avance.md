---
author_gravatar: http://1.gravatar.com/avatar/d6cd7628bc242b87449712f0fef53924?s=96&d=mm&r=g
author_fullname: David Blaisonneau
author: david-blaisonneau
tags: Actualité
feature: http://fablablannion.github.io/images/vlcsnap-2013-10-28-12h26m15s208.png
layout: post
slug: remise-en-marche-machines-du-fablab-avance
date: 2013-10-26
title: "La réhabilitation des machines du FabLab avance !"
comments: True
---
Lundi dernier, la réhabilitation des machines données au FabLab par le Lycée
Le Dantec a bien avanceé.

La machine de dépose de pâte à braser peut enfin être pilotée, cette machine
est la première étape dans la dépose de composants CMS (Pick N' Place). Cette
machine, la precidot, ne fonctionne qu'avec une disquette 3″1/2 🙂 Il nous a
donc fallu faire du rétro-engineering sur le binaire de la disquette pour
apprendre comment ajouter des lignes de dépose de pâte à braser. C'est donc un
petit programme Python qui analyse un fichier Eagle pour récupérer les points
de dépose, et écrit le tout sur la disquette. Nous espérons bientôt pouvoir
tester la dépose de la pâte dés qu'un point d'arrivé d'air sera disponible (la
dépose fonctionne sous pression d'air). Voici ce que cela donne au finale:

C'est aussi la machine CNC CharlyRobot qui a repris 2 degrés de liberté: les
axes X/Y sont enfin pilotables depuis LinuxCNC ! Cette machine, arrivée sans
carte de commande, s'est donc vu ajouter une carte de commande de puissance
avec des ponts en H, le tout dans la méthode DIY (carte entièrement conçu au
FabLab). Il a aussi fallu trouvé la méthode pour alimenter le tout. Bravo
[@theo](http://fablab-lannion.org/membres/theo/), épaulé par
[@pofexpray](http://fablab-lannion.org/membres/pofexpray/) ! Il reste encore
l'axe Z, la finalisation de l’électronique et le carter, mais ça avance vite
et c'est précis! la preuve:

Si vous êtes intéressé, n'hésitez pas à passer.


