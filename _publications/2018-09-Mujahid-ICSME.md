---
title: "Studying permission related issues in Android Wearable apps"
collection: publications
authors: 'Suhaib Mujahid,  Rabe Abdalkareem,  Emad Shihab'
permalink: /publication/2018-09-Mujahid-ICSME
date: 2018-09-01
venue: 'Proceedings of the 2018 IEEE International Conference on Software Maintenance and Evolution (ICSME)'
preprent: '/papers/Mujahid_ICSME2018.pdf'
---
 **Abstract:**  Wearable devices are becoming increasingly popular; these devices host software that is known as wearable apps. Wearable apps could be packaged alongside handheld apps, hence they must be installed on the accompanying device (e.g., smartphone). This device dependency causes both apps to be also tightly coupled. Most importantly, when a wearable app is distributed by embedded it in a handheld app, Android Wear platform requires to include the wearable permission also in the handheld app which is error-prone. In this paper, we defined two permission issues related to wearable apps-namely permission mismatches and superfluous features. To study the permission related issues, we propose a technique to detect permission issues in wearable apps. We implement our technique in a tool called Permlyzer, which automatically detects these permission issues from an app&apos;s APK. We run Permlyzer on a dataset of 2,724 apps that have embedded wearable version and 339 standalone wearable app. Our result shows that I) 6% of wearable apps that request permissions are suffering from the permission mismatching problem; II) out of the apps that requires underlying features, 523 (52.4%) of handheld apps and 66 (80.5%) of standalone wearable apps have at least one superfluous feature; III) all the studied apps missed a declaration of underlying features for one or more of their permissions, which shows that developers may not know the mapping between the permissions they request and the hardware features. Additionally, in a survey of wearable app developers, all of the developers that responded mention that having a tool like Permlyzer, that detect permission related issues would be useful to them. Our results contribute to the understanding of permissions related issues in wearable apps, in particular, proposing a technique to detect permission mismatch and superfluous features.

DOI: [10.1109/ICSME.2018.00043](https://doi.org/10.1109/ICSME.2018.00043){:target="_blank"}
