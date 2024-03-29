---
layout: default
title: RedDawn
nav_order: 2
has_children: false
permalink: /docs/signature/reddawn
nav_exclude: true
---

# RedDawn

## High-level Description

* Year: 2018
* Blog: https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/malware-on-google-play-targets-north-korean-defectors/

This malware sample aims to steal information and perform an unknown payload. The malware activates on application launch. It schedules a task that repeats on accessibility events. It then aims to steal device and user-specific information (ex., phone number, social accounts) from the user. Lastly, it retrieves a command and executable from the server and executes an unknown payload when the screen is off. Additionally, the malware also contains an ambiguous setting (labelled "special functionality") that enables device admin privileges to increase difficulty in uninstalling the application.

## Signature
---

The image of the signature can be downloaded [here](../../img/signatures/RedDawn.png) for closer inspection.

![](../../img/signatures/RedDawn.png)