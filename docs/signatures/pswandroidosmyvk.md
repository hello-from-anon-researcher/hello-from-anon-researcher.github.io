---
layout: default
title: PSWAndroidOSMyVk
nav_order: 2
has_children: false
permalink: /docs/signature/pswandroidosmyvk
nav_exclude: true
---

# PSWAndroidOSMyVk

## High-level Description

* Year: 2017
* Blog: https://securelist.com/still-stealing/83343/

This malware sample aims to steal VK credentials from the user. The malware sample checks that the user is from a specific region of the world (i.e., Russia or Ukraine). It then opens the legitimate VK website. A local javascript payload collects users credential on login, the malware retrieves the credentials in a javascript interface and leaks the information to the malware developers server in direct bytecode.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/PSWAndroidOSMyVk.png) for closer inspection.

![](../../img/signatures/PSWAndroidOSMyVk.png)