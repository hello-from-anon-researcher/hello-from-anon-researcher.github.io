---
layout: default
title: TrojanAgentDropperGY
nav_order: 2
has_children: false
permalink: /docs/signature/trojandropperagentgy
nav_exclude: true
---

# TrojanAgentDropperGY

## High-level Description

* Year: 2016
* Blog: https://www.welivesecurity.com/2016/08/03/fake-prisma-apps-found-google-play/

This malware sample aims to steal user information. On application launch, the malware hides the app icon. Upon the user clicking a button, the malware opens a scam page (e.g., fake "you win" pages) where the user enters personal information for a prize (an observed behavior, as the scam page was down at time of analysis). User-specific information entered witin the scam link is sent to the malware developer as a result. The malware also schedules a task, on application launch or boot system events, that retrieves commands and an executable that opens a login page to steal the user's social account (an observed behavior, as the server to download the executable was down).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/TrojanDropperAgentGY.png) for closer inspection.

![](../../img/signatures/TrojanDropperAgentGY.png)
