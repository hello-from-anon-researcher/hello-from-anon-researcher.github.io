---
layout: default
title: Haken
nav_order: 2
has_children: false
permalink: /docs/signature/haken
nav_exclude: true
---

# Haken

## High-level Description

* Year: 2020
* Blog: https://research.checkpoint.com/2020/android-app-fraud-haken-clicker-and-joker-premium-dialer/

The malware sample aims to perform ad-click fraud. It listens on a wide variety of system-wide events to schedule two threads which: (1) contact the malware developers server for commands to push full screen ads, and (2) perform a probability roll to pick an ad vendor that displays ads disruptively to the user. The malware then performs ad-click fraud behavior upon retrieving an enable flag from commands in the first thread.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/Haken.png) for closer inspection.

![](../../img/signatures/Haken.png)