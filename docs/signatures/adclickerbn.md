---
layout: default
title: AdClickerBN
nav_order: 2
has_children: false
permalink: /docs/signature/adclickerbn
nav_exclude: true
---

# AdClickerBN

## High-level Description

* Year: 2017
* Blog: https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/android-click-fraud-apps-briefly-return-google-play/

This malware sample contains the ability to perform ad-click fraud on the unsuspected user (an observed behavior, as the server was down at time of analysis). On application launch, the malware attempts to request device admin privileges to make it more difficult to uninstall the application. To perform the main malicious behavior, the malware listens on connectivity change and checks whether the internet is available. The sample retrieves commands and JavaScript code containing the payload from the Internet. It then runs the retrieved JavaScript in a WebView. An alarm repeats the ad click fraud process.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/AdClickerBN.png) for closer inspection.

![](../../img/signatures/AdClickerBN.png)