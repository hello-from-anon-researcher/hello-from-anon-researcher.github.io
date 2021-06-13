---
layout: default
title: HidenAdHRXH
nav_order: 2
has_children: false
permalink: /docs/signature/hidenadhrxh
nav_exclude: true
---

# HidenAdHRXH

## High-level Description

* Year: 2019
* File Hash (SHA-256): 776b0a9e5d06a239579ea758c76db46dc0fcd5662bc8d257ed97ec9af5a1b844
* Blog: https://www.trendmicro.com/en_us/research/19/h/adware-posing-as-85-photography-and-gaming-apps-on-google-play-installed-over-8-million-times.html

This malware application aims to aggressively push full screen ads to the user. On app launch, the malware checks two time bombs based on current system times, and times retrieved from a C&C server. Upon the amounts of time passed, the app hides its icon and registers a receiver on device status system events (i.e., when the device is unlocked). Lastly, an ad is displayed to the user, an alarm is scheduled to periodically push ads to the user when the screen is on.

## Signature
---

![](../../img/signatures/HidenAdHRXH.png)