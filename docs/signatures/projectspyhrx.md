---
layout: default
title: ProjectSpyHRX
nav_order: 2
has_children: false
permalink: /docs/signature/projectspyhrx
nav_exclude: true
---

# ProjectSpyHRX

## High-level Description

* Year: 2020
* Blog: https://blog.trendmicro.com/trendlabs-security-intelligence/coronavirus-update-app-leads-to-project-spy-android-and-ios-spyware/

This malware aims to steal user information. It first checks the Android version and requests notification listener service permissions. It then runs four/five different threads depending on the Android version to (1) steal device information, (2) steal SMS/contacts/call history, (3) steal stored files within the WhatsApp folder, (4) steal voice notes from the WhatsApp folder, and (5) steal notification messages from five different applications (facebook, facebook messenger, threema, telegram, whatsapp).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/ProjectSpyHRX.png) for closer inspection.

![](../../img/signatures/ProjectSpyHRX.png)
