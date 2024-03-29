---
layout: default
title: SpyBankerPV
nav_order: 2
has_children: false
permalink: /docs/signature/spybankerpv
nav_exclude: true
---

# SpyBankerPV

## High-level Description

* Year: 2017
* Blog: https://www.welivesecurity.com/2017/11/21/new-campaigns-spread-banking-malware-google-play/

This malware sample attempts to install and perform an unknown payload. The malware hides the app icon upon launching the application. The initial activation of the malware relies on either (1) the application launching or (2) when the device boots, is not a sandbox, a user-specific application is not already installed, and is not in a specific location (i.e., Russia or Ukraine). It then requests device admin privileges. After a set period of time, it retrieves commands and an executable from it's C&C server. It checks that the executable has not been tampered with before attempting to ask the user to install it to perform an unknown payload.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/SpyBankerPV.png) for closer inspection.

![](../../img/signatures/SpyBankerPV.png)