---
layout: default
title: SMSAndroidOSWesp
nav_order: 2
has_children: false
permalink: /docs/signature/smsandroidoswesp
nav_exclude: true
---

# SMSAndroidOSWesp

## High-level Description

* Year: 2017
* Blog: https://securelist.com/expensive-free-apps/77083/

This malware sample aims to perform premium charges via SMS. The malware contacts it's C&C server initially to ensure the server is up. It then checks to make sure the network operator matches a certain string (e.g., "RANG"). 
The user then inputs a phone number and malware verifies the input. The phone number is sent to the malware developers server to subscribe the number to an online service, yourmob.com. This sample also contains capabilities to intercept SMS messages to retrieve confirmation codes from the online service to confirm the premium charge.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/SMSAndroidOSWesp.png) for closer inspection.

![](../../img/signatures/SMSAndroidOSWesp.png)
