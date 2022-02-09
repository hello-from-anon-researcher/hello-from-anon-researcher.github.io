---
layout: default
title: InstaDetector
nav_order: 2
has_children: false
permalink: /docs/signature/instadetector
nav_exclude: true
---

# InstaDetector

## High-level Description

* Year: 2016
* Blog: https://www.pandasecurity.com/mediacenter/social-media/we-know-whos-viewed-your-instagram-and-its-not-who-you-think/, https://securelist.com/who-viewed-you-instagram-account-and-who-stole-your-password/74260/

This malware application aims to steal instagram credentials. The user presses a begin button upon launch and a WebView is opened as a result with a fake instagram login page (the site was still up at analysis time). Credentials are stolen once the user inputs the sensitive data and presses the login button.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/InstaDetector.png) for closer inspection.

![](../../img/signatures/InstaDetector.png)
