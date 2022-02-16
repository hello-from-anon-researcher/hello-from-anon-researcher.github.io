---
layout: default
title: SockBot
nav_order: 2
has_children: false
permalink: /docs/signature/sockbot
nav_exclude: true
---

# SockBot

## High-level Description

* Year: 2017
* Blog: https://www.symantec.com/connect/blogs/android-malware-google-play-adds-devices-botnet-and-performs-ddos-attacks

This malware sample aims to perform web traffic boosting. It retrieves ad configuration from the malware developers server on device boot when network is available. The malware sample then aims to connect to an ad server to perform ad requests (an observed behavior, as the server was down).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/SockBot.png) for closer inspection.

![](../../img/signatures/SockBot.png)
