---
layout: default
title: FalseGuide
nav_order: 2
has_children: false
permalink: /docs/signature/falseguide
nav_exclude: true
---

# FalseGuide

## High-level Description

* Year: 2017
* Blog: https://blog.checkpoint.com/2017/04/24/falaseguide-misleads-users-googleplay/

This malware sample aims to perform privilege abuse, and run an unknown payload. Device admin privileges are requested upon launching the application to increase difficulty of uninstallation. The app further retrieves commands from Firebase messaging services to download a payload. It then runs the payload on boot complete or after receiving the message.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/FalseGuide.png) for closer inspection.

![](../../img/signatures/FalseGuide.png)
