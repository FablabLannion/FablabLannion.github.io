---
layout: page
permalink: /trender/
title: Trender
description: "Trender.."
tags: [trender, user guide, configuration, manuel]
imagefeature: images/trender/trender.png
chart: false
---

![Trender](images/trender/trender.png)

> "Er c'houlzadoù teñvalant e ranker en em soñjal evit gwelet ar gouloù..." Aristote Onassis

Ur pezh graet da zreuzfumiñ titouroù e gouloù eo an Trender

*Lenn en eur yezh all: [English](trender.md), [Français](trender.fr.md), [Brezhoneg](trender.bzh.md)*

## Taolenn
  - [Stummoù](#Stummoù)
    - [Munuter](#Munuter)
    - [Demo](#demo)
    - [gouzav](#gouzav)
  - [Q&A](#q&a)

Stagit an Trender diouzh an tredan dre ar fulenn USB. War enaou e zle mont ar mekanik

## Stummoù

Meur a stumm a zo gant an Trender
 * Demo
 * Munuter
 * Sistem gouzav  (twitter, jenkins,...)

A-fell e krogo an Trender gant ar stumm gouzav

![Color](images/trender/modes-fr.png)

Evit chench eus ar stumm gouzav da vunuter, skrivit *1* e plas stumm er roll **Configure Wifi**
Gant ur goulou gwer e vo kardarnaet o choaz.

Ur wech aet er stumm munuter, eo ret adloc'han an Trender evit adkavout ar stumm gouzav.


### Munuter

Ur munuter a rikouro ac'hanoc'h meran gwelloc'h o amzer. Gant an Trender ez eus tu personelañ
3 gwehin

Er roll "WiFi configure", ur wech chenchet ar stumm, distroit war ar bajenn bennan
(http://192.168.4.1).

Moien e vo deoc'h neuze
  * Personelañ ho munuter
  * Loc'han  ho munuter
  * Paouezan  ho munuter
  * Kaout titouroù rouedad an Trender
  * Kregin gant ar stumm demo

![Color](images/trender/tk.png)

Choazit ar roll **TIMEKEEPER CONFIGURATION**

#### Configuration

Tu zo deoc'h personelañ:
 * une durée totale
 * 3 étapes intermédiaires

![Color](images/trender/color.png)

La durée et les étapes peuvent être définies comme suit:

![Color](images/trender/timekeeper-fr.png)


### Démo

Le mode Démo peut être démarré depuis le menu Minuteur.
Sélectionnez le sous menu **Color** puis sélectionner  **rainbow** (jeu de
lumières aléatoires) ou choisissez votre couleur favorite via le sélecteur.

![Color](images/trender/demo_color.png)


### Notification

Le Trender peut transformer des notifications en lumière.
Vous devez configurer le point d'accès et le channel ThingSpeak https://thingspeak.com/.

La procédure pour démarrer votre trender est:
  * Depuis votre téléphone ou votre ordinateur, sélectionner le réseau WiFI dont le SSID commence par TRENDER-
  * Si aucune fenêtre n'apparaît, ouvrez un navigateur Internet et tapez http://192.168.4.1

Vous devriez voir l'écran suivant:

![Main screen](images/trender/main.png)

 1. Configure WiFi
 2. Configure WiFi (No Scan)
 3. Info
 4. Reset

#### Configure WiFi

Le menu "Configure WiFi" permet de connecter le Trender à Internet via une passerelle (boxe Internet, Téléphone, ..) ainsi que le channel ThingSpeak de notification.

Le Trender se reconnectera automatiquement à un point d'accès déjà configuré
si il a été configuré précédemment et si le réseau est disponible.
Il est possible depuis ce menu de lister tous les réseaux WiFi disponibles.

![Notif](images/trender/ThingSpeak.png)

TODO config ThinkSpeak

#### Configure WiFi (No Scan)

Le menu "Configure WiFi (No scan)" permet de configurer le mode notification et plus précisément le channel ThingSpeak.

#### Info

Ce menu fournit des informations sur le Trender (Chip ID, Adresse IP, MAC, ...).

#### Reset

Ce menu permet de reconfigurer le Trender dans son état initial.
**Attention tous les paramètres de configuration seront effacés!**

Les paramètres de connexion WiFI sont notamment effacés.


## Q&A

Q: Où est le code?
A: https://github.com/FablabLannion/Trender

Q: Une autre référence?
A: Une page wiki (en Français) est disponible http://wiki.fablab-lannion.org/index.php?title=Trender

Q: Qui contacter?
A: par mail trender@fablab-lannion.org, ou sur twitter.com/fablablannion
