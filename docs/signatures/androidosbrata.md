---
layout: default
title: AndroidOSBrata
nav_order: 2
has_children: false
permalink: /docs/signature/androidosbrata
nav_exclude: true
---

# AndroidOSBrata

## High-level Description

* Year: 2019
* Blog: https://securelist.com/spying-android-rat-from-brazil-brata/92775/

This malware sample aims to abuse accessibility permissions and performs a series of malicious behaviors based on commands sent from the C&C server. On application launch, the malware attempts to request accessibility permissions and hides the app icon. Once certain UI indicators appear on the screen (e.g., settings indicators) the malware performs automated gesture input hiding techniques to prevent the user from certain actions. Depending on commands retrieved from the server, the malware can: (1) steal device/user-specific information (phishing credentials, capturing the screen), (2) launch applications, (3) perform self-uninstallation

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/AndroidOSBrata.png) for closer inspection.

![](../../img/signatures/AndroidOSBrata.png)
