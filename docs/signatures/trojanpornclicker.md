---
layout: default
title: TrojanPornClicker
nav_order: 2
has_children: false
permalink: /docs/signature/trojanpornclicker
nav_exclude: true
---

# TrojanPornClicker

## High-level Description

* Year: 2016
* Blog: https://blog.malwarebytes.com/cybercrime/2016/06/trojan-clickers-gaze-cast-upon-google-play-store/

This malware sample aims to perform ad-click fraud. It schedules a repeating task on network system events or application launch. The malware then retrieves ad configuration and commands from the malware developer's server to perform ad-click fraud (an observed behavior, as the server was down at time of analysis). This malware sample also contains the ability to hide it's app icon on application launch based on a button click from the user.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/TrojanPornClicker.png) for closer inspection.

![](../../img/signatures/TrojanPornClicker.png)
