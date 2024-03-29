---
layout: default
title: SpyBankerAJZ
nav_order: 2
has_children: false
permalink: /docs/signature/spybankerajz
nav_exclude: true
---

# SpyBankerAJZ

## High-level Description

* Year: 2018
* Blog: https://www.welivesecurity.com/2018/12/11/android-trojan-steals-money-paypal-accounts-2fa/

This malware sample aims to steal various account credentials and banking information from the user. The malware sample creates multiple tasks after the user grants accessibility permissions. Two tasks retrieve commands from the malware developers server to collect: (1) phishing website links (an observed behavior, as the phishing site was down), and (2) commands to enable phishing. It then can phish for credentials and account balance for four brazilian banks. To identify account balance, the malware checks for UI indicators on the screen. In addition to the four banks, it also aims to steal account credentials to popular entertainment and social websites (an observed behavior, as the phishing site was down). Lastly, the malware abuses accessibility permissions to perform automated-gesture input to press the back button on certain installed applications.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/SpyBankerAJZ.png) for closer inspection.

![](../../img/signatures/SpyBankerAJZ.png)
