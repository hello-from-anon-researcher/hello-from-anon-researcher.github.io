---
layout: default
title: ToastAmigo
nav_order: 2
has_children: false
permalink: /docs/signature/toastamigo
nav_exclude: true
---

# ToastAmigo

## High-level Description

* Year: 2017
* Blog: https://blog.trendmicro.com/trendlabs-security-intelligence/toast-overlay-weaponized-install-android-malware-single-attack-chain/

This malware sample aims to perform ad-click fraud and steal user information. Once gaining accessibility permissions, it sends device information to the malware developers server. The malware sample then retrieves an additional application and a set of commands. The additional application requests device admin privileges and listens on previously sent commands to perform: (1) ad-click fraud, (2) steal google account credentials, and (3) perform screen locking (all observed behaviors, as the server to retrieve the additional application was down).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/ToastAmigo.png) for closer inspection.

![](../../img/signatures/ToastAmigo.png)
