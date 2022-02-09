---
layout: default
title: LightsOut
nav_order: 2
has_children: false
permalink: /docs/signature/lightsout
nav_exclude: true
---

# LightsOut

## High-level Description

* Year: 2018
* Blog: https://research.checkpoint.com/2018/malicious-flashlight-apps-google-play/

This malware application aims to push full screen ads. It listens to call events (new outgoing call, phone state change), and displays ads upon the phone hanging up. The malware further contains capabilities to hide the icon based on (1) the device (must not be a xiaomi, huawei, vivo, or oppo phone), and (2) configuration from the server.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/LightsOut.png) for closer inspection.

![](../../img/signatures/LightsOut.png)
