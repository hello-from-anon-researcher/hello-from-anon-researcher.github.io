---
layout: default
title: FakeInsta
nav_order: 2
has_children: false
permalink: /docs/signature/fakeinsta
nav_exclude: true
---

# FakeInsta

## High-level Description

* Year: 2019
* Blog: https://blog.malwarebytes.com/cybercrime/2019/04/instagram-password-stealing-apps-found-on-google-play/

This malware application opens a fake instagram login page to phish social account credentials from the user. On launch of the application, the sample opens a web page to the user. Once the user presses a button to login, it provides a fake phishing page (the site was available at the time). When the user enters sensitive information and presses the login button, the sample leaks their credentials to the malware developer.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/FakeInsta.png) for closer inspection.

![](../../img/signatures/FakeInsta.png)
