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
* Blog: https://www.welivesecurity.com/2019/02/08/first-clipper-malware-google-play/

This malware sample aims to hijack the user's text clipboard. Upon launch of the application, the sample registers a clipboard listener. When the user clipboards text, it checks the data format to make sure it is a wallet address. If the text is a wallet address, the malware sample replaces the address with a hardcoded string of the malware developer's.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/ClipperC.png) for closer inspection.

![](../../img/signatures/ClipperC.png)