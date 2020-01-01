---
layout: default
title: Home
nav_order: 1
description: "What is my Machine Learning!? The Challenges of Static Android Malware Detection"
permalink: /
---

### What is my Machine Learning!? The Challenges of Static Android Malware Detection

---

Due to the rising popularity of smart phones, malware in the Android field has been increasing exponentially. A number of approachs have emerged recently to combat the amount of malware growth in mobile markets. These approaches mainly work by statically extracting features of an app, and training a machine learning classifier to capture high level properties of the apps. The proposed detection tools evaluate on typical datasets provided through academia. However, this raises one important question--how do these proposed tools perform in a real world environment? We focus on new malware samples which are particularly difficult to detect: samples that penetrated the Google Play store, arguably containing the best defense for Android. From our experiment, we find that:

1. As malicious and benign apps become larger and their functionality becomes more varied, the tools are more susceptible to confusion from "noisy" features
2. In several cases, malicious functionality of the app is not packed within the app, but rather downloaded dynamically at runtime
3. All tools are easily confused by the presence of dead code and Android permissions

This repository contains artifacts used to perform the experiments defined within the paper. We tried our best to anonymize all information which can be related back to the authors of the paper.
