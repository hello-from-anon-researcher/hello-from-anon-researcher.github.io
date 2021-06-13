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
* File Hash (SHA-256): 50247e85ecb6452aa847a572ca04ab310cf8e9288520f824d13ebcc207be7c13
* Blog: https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/android-click-fraud-apps-briefly-return-google-play/

This malware sample contains the ability to perform ad-click fraud on the unsuspected user. To perform this malicious behavior, the malware listens on connectivity change and checks whether the internet is available. Commands and javascript code to perform the payload are retrieved from the internet, and the ad-click fraud is performed using the retrieved javascript code. An alarm is scheduled to repeat this process.

## Signature
---

![](../../img/signatures/AdClickerBN.png)