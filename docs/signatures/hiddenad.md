---
layout: default
title: HiddenAd
nav_order: 2
has_children: false
permalink: /docs/signature/hiddenad
nav_exclude: true
---

# HiddenAd

## High-level Description

* Year: 2018
* Blog: https://nakedsecurity.sophos.com/2018/03/23/crooks-infiltrate-google-play-with-malware-lurking-in-qr-reading-utilities/

This malware application aims to push full screen ads to the user. The malware implements an alarm based on application launch, and boot/network system events to routinely leak device information to the malware developers server. It then retrieves commands from the server and disruptively pushes ads to the user. The malware dynamically registers device status system events that push ads disruptively to the user depending on the commands from the server.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/HiddenAd.png) for closer inspection.

![](../../img/signatures/HiddenAd.png)