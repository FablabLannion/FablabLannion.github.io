---
layout: page
permalink: /trender/
title: Trender
tags: [trender, user guide, configuration, manuel]
imagefeature:trender.png
chart: false
---
Trender
============

The Trender is an objet translating different types of information into light.

*Read this in other languages: [English](README.md), [Français](README.fr.md), [Brezhoneg](README.bzh.md)*

## Table of Contents
  - [Get started](#get-started)
  - [Modes](#modes)
    - [Time keeper](#time-keeper)
    - [Notification](#notification)
    - [Demo](#demo)
  - [FAQ](#faq)

## Get started
The procedure to setup your Trender is:
  * Connect your Trender to a power supply through the USB cable, a light cycle will start to indicate that the Trender is properly powered.
  * From your mobile phone or your computer, select the Wifi network whith SSID starting with TRENDER-
  * If the pop-up connection window is not automatically displayed, open a web browser and enter the url http://192.168.4.1

You should see the following screen:

![Main screen](trender/main.png)

 1. Configure WiFi
 2. Configure WiFi (No Scan)
 3. Info
 4. Reset

### Configure WiFi

The "Configure WiFi" mode allows to connect the Trender to the Web.
The Trender will connect automatically if it has been already configured.
It is possible to scan all the access points.

### Configure WiFi (No Scan)

The "Configure WiFi (No scan)" can be used to configure only the ThingSpeack channel.

### Info

This menu provides Trender physical information (Chip ID, IP Address, MAC, ...).

### Reset

This menu can be used to perform a factory reset. All the previous parameters
(especially the WiFi configuration) are cleaned and the mode is set back to notification.



## Modes

The Trender supports several modes. You can use it as:
 * Demo
 * Timekeeper
 * Notification system (twitter, jenkins)

By default the Trender is in Notification mode.

You can switch from Notification to Timekeeper mode by putting *1* in the mode
window in the **Configure WiFi** mode. A green light will blink to indicate that the mode has been changed.

Once in timekeeper mode, you may come back to notification mode by putting *0*
in the mode window or clicking on the **Reset** menu.


### Timekeeper

A timekeeper is often referred to as a time clock, which tracks time. The
Trender allows to set 3 fully customizable thresholds.

From the WiFi configure menu, once you set *1* in the mode window, come back to
the main page. A new menu will be displayed.

![Color](trender/tk.png)

Select the menu **TIMEKEEPER CONFIGURATION**

#### Configuration

You can configure:
 * the duration
 * 3 intermediate steps

![Color](trender/color.png)

The duration and different timers can be defined as follows:

![Color](trender/timekeeper-en.png)


### Notification

The Trender may translate web information into light.
You must configure a web public access point. You must select the SSID and
enter the password. Then you must select the ThingSpeak channel ID.

![Notif](trender/ThingSpeak.png)


### Demo

The Demo mode can be started from the Timekeeper menu.
Select the submenu **Color** then tick **rainbow** or choose the color you want.

## FAQ
