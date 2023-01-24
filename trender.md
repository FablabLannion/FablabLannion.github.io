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

> "It is during our darkest moments that we must focus to see the light." Aristote Onassis

The Trender is an objet translating different types of information into light.

*Read this in other languages: [Français](/trender_fr)*

## Table of Contents
- [Modes](#modes)
  - [Timekeeper](#timekeeper)
  - [Demo](#demo)
  - [Notification](#notification)
- [FAQ](#faq)

Connect your Trender to a power supply through the USB cable, a light cycle will start to indicate that the Trender is properly powered.

## Modes

The Trender supports several modes. You can use it as:
 * Timekeeper
 * Demo
 * Notification system (twitter, jenkins,...)

By default the Trender is in Notification mode.

![Color](images/trender/modes.png)

You can switch from Notification to Timekeeper mode by putting *1* in the mode
window of the **Configure WiFi** menu.
A green light will blink to indicate that the mode has been changed.
The trender will restart and a new page will be displayed on the http://192.168.4.1.

Once in timekeeper mode, you may come back to notification after Trender power restart.


### Timekeeper

A timekeeper is often referred to as a time clock, which tracks time. The
Trender allows to set 3 fully customizable thresholds.

From the WiFi configure menu, once you set *1* in the mode window, come back to
the main page. A new menu will be displayed.

You can:
  * Cutomize your timekeeper
  * Start your timekeeper
  * Stop your timekeeper
  * Get network info
  * Start the Demo mode

![Color](images/trender/tk.png)

Select the menu **TIMEKEEPER CONFIGURATION**

#### Configuration

You can configure:
 * the duration
 * 3 intermediate steps

![Color](images/trender/color.png)

The duration and different timers can be defined as follows:

![Color](images/trender/timekeeper-en.png)


### Demo

The Demo mode can be started from the Timekeeper menu.
Select the submenu **Color** then tick **rainbow** or choose the color you want.

![Color](images/trender/demo_color.png)


### Notification

The Trender may translate web information into light.
You must configure a web public access point. You must select the SSID and
enter the password. Then you must select the ThingSpeak channel ID https://thingspeak.com/.

The procedure to setup your Trender is:
  * From your mobile phone or your computer, select the WiFi network whith SSID starting with TRENDER-
  * If the pop-up connection window is not automatically displayed, open a web browser and enter the url http://192.168.4.1

You should see the following screen:

![Main screen](images/trender/main.png)

 1. Configure WiFi
 2. Configure WiFi (No Scan)
 3. Info
 4. Reset

#### Configure WiFi

The "Configure WiFi" menu allows to connect the Trender to the Web as well as the ThingSpeak channel for the Notification mode.
The Trender will connect automatically if it has been already configured and if the network is reachable.
It is possible to scan all the access points.

![Notif](images/trender/ThingSpeak.png)

TODO ThingSpeak

#### Configure WiFi (No Scan)

The "Configure WiFi (No scan)" menu can be used to configure only the ThingSpeack channel.

#### Info

This menu provides Trender physical information (Chip ID, IP Address, MAC, ...).

#### Reset

This menu can be used to perform a factory reset. **Be careful! All the previous parameters
(especially the WiFi configuration) will be cleaned.**



## FAQ

Q: Where is the code?
A: https://github.com/FablabLannion/Trender

Q: Any other reference?
A: A wiki page (in French) is available http://wiki.fablab-lannion.org/index.php?title=Trender

Q: Who may I contact in case of trouble?
A: mail trender@fablab-lannion.org, twitter.com/fablablannion
