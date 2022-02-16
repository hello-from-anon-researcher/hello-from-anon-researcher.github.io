---
layout: default
title: Reputation1
nav_order: 2
has_children: false
permalink: /docs/signature/reputation1
nav_exclude: true
---

# Reputation1

## High-level Description

* Year: 2018
* Blog: https://www.symantec.com/blogs/threat-intelligence/persistent-malicious-apps-google-play

This malware sample aims to display full screen ads to the user and steal user-specific information. The malware first requests device admin privileges on launching the application. It then registers a routine that periodically collects commands from the server. The command can be one of the following: (1) display full screen ads, (2) open a scam link to retrieve user-specific information (an observed behavior as the server was down).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/Reputation1.png) for closer inspection.

![](../../img/signatures/Reputation1.png)
