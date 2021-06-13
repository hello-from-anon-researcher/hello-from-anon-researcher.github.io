---
layout: default
title: ClipperC
nav_order: 2
has_children: false
permalink: /docs/signature/clipperc
nav_exclude: true
---

# ClipperC

## High-level Description

* Year: 2019
* File Hash (SHA-256): ea5742cf2a6087577028049e47ecb4a24c9a6e7db872a8c90ee0145f22811599
* Blog: https://www.welivesecurity.com/2019/02/08/first-clipper-malware-google-play/

This malware sample aims to hijack the users text clipboard. Upon launching the application, it registers a clipboard listener. When the user clipboards text, it checks the data format to make sure it is a wallet address. If the text is a wallet address, it replaces the address with a hardcoded string of the malware developers.

## Signature
---

![](../../img/signatures/ClipperC.png)