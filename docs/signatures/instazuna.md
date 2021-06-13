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
* File Hash (SHA-256): 5839066d09e52d1e406648058dabf1ee979e3139bfc44713c82410bd28c705ad
* Blog: https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/turkish-instagram-password-stealers-found-google-play/

This malware application aims to steal instagram credentials from the user. Upon launching the application, the app launches a remote website. Once the user selects the login button on the website and inputs their credentials, their instagram credentials are leaked to the malware developer.

## Signature
---

![](../../img/signatures/InstaZuna.png)