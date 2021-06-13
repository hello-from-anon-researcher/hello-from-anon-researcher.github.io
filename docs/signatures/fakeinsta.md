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
* File Hash (SHA-256): 4c299a84230a432232b0bb2df25b293c18cf2ed419fb6f62623b9b89b8181df9
* Blog: https://blog.malwarebytes.com/cybercrime/2019/04/instagram-password-stealing-apps-found-on-google-play/

This malware application opens a fake instagram login page to phish social account credentials from the user. On launching the application, a web page is opened to the user. Once the user presses a button to login, a fake phishing page is provided. Once the user enters sensitive information and presses the login button, the credentials are leaked to the malware developer.

## Signature
---

![](../../img/signatures/FakeInsta.png)