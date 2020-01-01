---
layout: default
title: Data Sets
nav_order: 3
has_children: false
permalink: /docs/datasets
parent: Artifacts
---

# Data Sets
---
<span style="color:red">NOTE: We would like to ensure the data sets are not being distributed for malicious purposes. If you would like to acquire our GP malware dataset or file hashes of VT malware + Benign apps B, please contact us by emailing hello-from-anon-researcher@outlook.com.</span>

## Overview
---
The overall number of samples for each data set is described below:

![](../img/data_set_summary.png)

## GP malware
---
### App Source Distribution
The distribution of GP malware apps collected from various sources are listed below:

![](../img/app_source_distributions.png)

A majority of our applications were found within alternative markets. We could not find any of our Google Play malware samples from our Virus Total Academic snapshots.

### Collected GP Malware Samples
We list the indicator of compromise (i.e., file hash, package name, app + author name) used to find each of our 1308 GP malware samples below:

|Indicator of Compromise|2016|2017|2018|2019|Total|
|:-------------------------------|:------------------:|:------:|:------:|:------:|:-----:|
|File Hash|51|136|17|10|214|
|Package Name|36|534|306|139|1015|
|App+Author Name|21|33|17|8|79|
|All|108|703|340|157|1308|

### GP Malware Samples Verification
The 214 GP malware samples collected from file hash are identical to samples reported from the blog. However, the remaining (1015+79) samples not found from file hash sources (i.e., malware repositories) may not contain the malicious behavior; it is possible for apps found through package name and app + author name to contain different code. To ensure these samples contain the same malicious behavior as ones reported within a Google Play malware blog, we verify each sample by either: (1) ensuring the file contains the same file hash, or (2) Virus Total reports the sample as the same family described within the blog (ex. Sophos Antivirus [reports](https://www.virustotal.com/gui/file/0d1a13056f58a94362c91f81ad391849ea368010807c62689961ab679174cd67/detection) Andr/Guerilla-D--which is the same family reported in the [blog](https://nakedsecurity.sophos.com/2018/05/10/watch-out-photo-editor-apps-hiding-malware-on-google-play/)). The following table describes the method of verification for GP malware samples collected through package name or app + author name:

|Verification|2016|2017|2018|2019|Total|
|:-------------------------------|:------------------:|:------:|:------:|:------:|:-----:|
|File Hash|34|340|257|129|760| 
|Family Name|23|227|66|18|334|

### GP Malware Family Statistics
The table below describes the number of families found, and min/max/med/mean samples collected per family:

|Statistic|2016|2017|2018|2019|Total|
|:-------------------------------|:------------------:|:------:|:------:|:------:|:-----:|
|# Families|18|48|25|11|102|
|Min|1|1|1|1|1|
|Max|33|227|64|84|227|
|Median|1.0|2.0|4|8|2.0|
|Mean|6.0|14.6|13.6|14.3|12.8|
