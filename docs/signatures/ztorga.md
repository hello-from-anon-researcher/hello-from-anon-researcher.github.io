---
layout: default
title: ZtorgA
nav_order: 2
has_children: false
permalink: /docs/signature/ztorga
nav_exclude: true
---

# ZtorgA

## High-level Description

* Year: 2017
* Blog: https://securelist.com/ztorg-from-rooting-to-sms/78775/

This malware sample perform premium charges or web traffic boosting. The malware sample schedules a repeating task on application launch. This task performs two tasks. The first task retrieves commands from the malware developer's server to perform premium charges, or open web pages to perform web traffic boosting. The second task triggers when the user receives an SMS message. It then can block incoming SMS messages depending on the command sent from the first task.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/ZtorgA.png) for closer inspection.

![](../../img/signatures/ZtorgA.png)