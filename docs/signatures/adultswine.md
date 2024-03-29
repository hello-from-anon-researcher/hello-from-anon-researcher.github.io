---
layout: default
title: AdultSwine
nav_order: 2
has_children: false
permalink: /docs/signature/adultswine
nav_exclude: true
---

# AdultSwine

## High-level Description

* Year: 2018
* Blog: https://research.checkpoint.com/2018/malware-displaying-porn-ads-discovered-in-game-apps-on-google-play/

This malware sample aims to push full screen ads to the user. It listens on a variety of system events (package replaced, developer defined, user present, boot complete, external applications available) and collects configuration from the malware developers server. It then dynamically registers a receiver on user present and screen off events. It collects illegitimate ads using screen off events, and displays the ads when the user is present (and screen is on). It further schedules an alarm that aims to: steal device information from the user, retrieve additional configuration, and hide the app icon upon response from the malware developers server.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/AdultSwine.png) for closer inspection.

![](../../img/signatures/AdultSwine.png)
