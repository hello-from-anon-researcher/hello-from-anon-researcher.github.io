---
layout: default
title: FakeFlash
nav_order: 2
has_children: false
permalink: /docs/signature/fakeflash
nav_exclude: true
---

# FakeFlash

## High-level Description

* Year: 2017
* File Hash (SHA-256): 559e8016ffd7fae2203446cb8ea724a5561f50c42230be18828394a65cfa9cf0
* Blog: https://www.welivesecurity.com/2017/04/04/dont-pay-free-malicious-adobe-flash-player-app-found-google-play/

This malware application opens scam links to steal information from the user. On launching the application, a local web file is loaded to persuade the user that flashplayer is outdated and provides a link the user can visit to "update flashplayer". The link opens a scam page which the malware developer steals sensitive information from the user.

## Signature
---

![](../../img/signatures/FakeFlash.png)