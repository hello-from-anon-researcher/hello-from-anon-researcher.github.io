---
layout: default
title: SpyBankerHU
nav_order: 2
has_children: false
permalink: /docs/signature/spybankerhu
nav_exclude: true
---

# SpyBankerHU

## High-level Description

* Year: 2017
* File Hash (SHA-256): 3bd7b3263ba89be9e64fc1ef786bb302240dbdd0378916aefa362390fc0a15a5
* Blog: https://www.welivesecurity.com/2017/02/22/sunny-chance-stolen-credentials-malicious-weather-app-found-google-play/

This malware sample contains the ability to phish banking credentials, based on brazilian banks. It collects commands from the malware developers C&C server to intercept SMS messages. Lastly, the malware contains the ability to block SMS messages after intercepting them.

## Signature
---

![](../img/signatures/spybankerhu.pdf)