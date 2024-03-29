---
layout: default
title: BKotlindHRX
nav_order: 2
has_children: false
permalink: /docs/signature/bkotlindhrx
nav_exclude: true
---

# BKotlindHRX

## High-level Description

* Year: 2018
* Blog: https://blog.trendmicro.com/trendlabs-security-intelligence/first-kotlin-developed-malicious-app-signs-users-premium-sms-services/, https://blog.malwarebytes.com/cybercrime/mobile/2018/02/mobile-menace-monday-first-kotlin-developed-malicious-app/

This malware sample aims to load a payload which performs premium charges based on WAP Billing. On launch of the application, the sample leaks device information (e.g., Device ID) to the server. It then checks the network connectivity of the device, and retrieves from the server a payload with commands. Based on the commands from the server, it performs a series of tasks required to subscribe the device to premium charges. In addition, the malware sample also contains capabilities of opening websites and running javascript code retrieved from the server (an observed behavior as the server was down at time of analyis).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/BKotlindHRX.png) for closer inspection.

![](../../img/signatures/BKotlindHRX.png)