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

This malware application aims to push full screen ads to the user. The malware implements an alarm based on boot events and application launch to routinely contact the malware developers server. It then retrieves commands from the server to either (1) push notifications that the user can click to perform web traffic boosting, or (2) collect ad configuration that is necessary to push full screen ads to the user.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/HiddenAd.png) for closer inspection.

![](../../img/signatures/HiddenAd.png)