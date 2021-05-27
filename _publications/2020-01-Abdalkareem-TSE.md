---
title: "A machine learning approach to improve the detection of CI skip commits"
collection: publications
authors: 'Rabe Abdalkareem,  Suhaib Mujahid,  Emad Shihab'
permalink: /publication/2020-01-Abdalkareem-TSE
date: 2020-01-01
venue: 'IEEE Transactions on Software Engineering Journal (TSE)'
preprent: '/papers/Abdalkareem_TSE2020.pdf'
---
 **Abstract:**  Continuous integration (CI) frameworks, such as Travis CI, are growing in popularity, encouraged by market trends towards speeding up the release cycle and building higher-quality software. A key facilitator of CI is to automatically build and run tests whenever a new commit is submitted/pushed. Despite the many advantages of using CI, it is known that the CI process can take a very long time to complete. One of the core causes for such delays is the fact that some commits (e.g., cosmetic changes) unnecessarily kick off the CI process. Therefore, the main goal of this paper is to automate the process of determining which commits can be CI skipped through the use of machine learning techniques. We first extracted 23 features from historical data of ten software repositories. Second, we conduct a study on the detection of CI skip commits using machine learning, where we built a decision tree classifier. We then examine the accuracy of using the decision tree in detecting CI skip commits. Our results show that the decision tree can identify CI skip commits with an average AUC equal to 0.89. Furthermore, the top node analysis shows that the number of developers who changed the modified files, the CI-Skip rules, and commit message are the most important features to detect CI skip commits. Finally, we investigate the generalizability of identifying CI skip commits through applying cross-project validation, and our results show that the general classifier achieves an average 0.74 of AUC values.

DOI: [10.1109/TSE.2020.2967380](https://doi.org/10.1109/TSE.2020.2967380){:target="_blank"}
