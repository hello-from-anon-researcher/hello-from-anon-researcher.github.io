---
layout: default
title: FakeFlash
nav_order: 2
has_children: false
permalink: /docs/signature/fakeflash
nav_exclude: true
---

# FakeFlash

## High-level Description

* Year: 2017
* Blog: https://www.welivesecurity.com/2017/04/04/dont-pay-free-malicious-adobe-flash-player-app-found-google-play/

This malware application opens scam links to steal information from the user. On launch of the application, the sample loads a local web file to persuade the user that flashplayer is out of date. It then provides a link that the user can visit to "update flashplayer". The link opens a scam page, which opens a paypal page for the user to perform premium charges for fake services (an observed behavior, as the server was down at time of analysis).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/FakeFlash.png) for closer inspection.

![](../../img/signatures/FakeFlash.png)
