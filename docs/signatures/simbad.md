---
layout: default
title: SimBad
nav_order: 2
has_children: false
permalink: /docs/signature/simbad
nav_exclude: true
---

# SimBad

## High-level Description

* Year: 2019
* Blog: https://research.checkpoint.com/2019/simbad-a-rogue-adware-campaign-on-google-play/

This malware aims to perform ad abuse payloads. The malware retrieves commands based on Parse push notifications which can: (1) hide the app icon and disruptively push ads to the user (requires commands retrieved in another path to enable ads), (2) retrieve commands from the malware developers server, (3) entice the user to download and install additional unknown payloads, (4) open a web phishing page (an observed behavior, as the server was down at time of analysis).

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/SimBad.png) for closer inspection.

![](../../img/signatures/SimBad.png)