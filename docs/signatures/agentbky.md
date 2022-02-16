---
layout: default
title: AgentBKY
nav_order: 2
has_children: false
permalink: /docs/signature/agentbky
nav_exclude: true
---

# AgentBKY

## High-level Description

* Year: 2017
* Blog: https://www.welivesecurity.com/2017/12/11/banking-malware-targets-polish-banks/

This malware attempts to steal banking credentials. Upon launching receiving a developer defined event (when firebase is initialized), the malware looks for target banking apps installed on the device. It then checks against 14 different banking applications and if found, attempts to open a web page to a phishing page (an observed behavior as the website was down at the time). It further has capabilities to launch the phishing pages on command based on push notifications using firebase cloud messaging services, that lead to the same phishing page behavior described above. Lastly, it contains a SMS stealing component that aims to steal SMS messages (likely the 2-Factor authentication code upon logging into the banking app).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/AgentBKY.png) for closer inspection.

![](../../img/signatures/AgentBKY.png)
