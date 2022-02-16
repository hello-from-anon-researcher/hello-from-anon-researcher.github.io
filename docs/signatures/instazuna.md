---
layout: default
title: InstaZuna
nav_order: 2
has_children: false
permalink: /docs/signature/instazuna
nav_exclude: true
---

# InstaZuna

## High-level Description

* Year: 2017
* Blog: https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/turkish-instagram-password-stealers-found-google-play/

This malware application aims to steal instagram credentials from the user. Upon launch of the application, the app launches a remote website. Once the user selects the login button on the website and inputs their credentials, the app leaks their instagram credentials to the malware developer (an observed behavior, as the phishing site was down).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/InstaZuna.png) for closer inspection.

![](../../img/signatures/InstaZuna.png)
