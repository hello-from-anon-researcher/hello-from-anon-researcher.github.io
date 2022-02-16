---
layout: default
title: Fakeyouwon
nav_order: 2
has_children: false
permalink: /docs/signature/fakeyouwon
nav_exclude: true
---

# Fakeyouwon

## High-level Description

* Year: 2019
* Blog: https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/unofficial-telegram-app-malicious-sites

This malware sample aims to perform ad-click fraud. The malware sample retrieves commands and a malicious executable on package events (Package Removed, Package Added) and boot events (Boot Complete). The malware sample then opens a webview and performs fraudulent clicks for ad revenue (an observed behavior, as server was down). 

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/Fakeyouwon.png) for closer inspection.

![](../../img/signatures/Fakeyouwon.png)
