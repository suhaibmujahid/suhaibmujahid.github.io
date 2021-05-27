---
title: "Which commits can be CI skipped?"
paper_id: Abdalkareem_TSE2019
collection: publications
authors: 'Rabe Abdalkareem,  Suhaib Mujahid,  Emad Shihab,  Juergen Rilling'
permalink: /publication/2019-02-Abdalkareem-TSE
date: 2019-02-01
venue: 'IEEE Transactions on Software Engineering Journal (TSE)'
series: 'TSE&apos;19'
preprint: '/papers/Abdalkareem_TSE2019.pdf'
---
 **Abstract:**  Continuous Integration (CI) frameworks such as Travis CI, automatically build and run tests whenever a new commit is submitted/pushed. Although there are many advantages in using CI, e.g., speeding up the release cycle and automating the test execution process, it has been noted that the CI process can take a very long time to complete. One of the possible reasons for such delays is the fact that some commits (e.g., changes to readme files) unnecessarily kick off the CI process. Therefore, the goal of this paper is to automate the process of determining which commits can be CI skipped. We start by examining the commits of 58 Java projects and identify commits that were explicitly CI skipped by developers. Based on the manual investigation of 1,813 explicitly CI skipped commits, we first devise an initial model of a CI skipped commit and use this model to propose a rule-based technique that automatically identifies commits that should be CI skipped. To evaluate the rule-based technique, we perform a study on unseen datasets extracted from ten projects and show that the devised rule-based technique is able to detect and label CI skip commits, achieving Areas Under the Curve (AUC) values between 0.56 and 0.98 (average of 0.73). Additionally, we show that, on average, our technique can reduce the number of commits that need to trigger the CI process by 18.16 percent. We also qualitatively triangulated our analysis on the importance of skipping the CI process through a survey with 40 developers. The survey results showed that 75 percent of the surveyed developers consider it to be nice, important or very important to have a technique that automatically flags CI skip commits. To operationalize our technique, we develop a publicly available prototype tool, called CI-Skipper , that can be integrated with any git repository and automatically mark commits that can be CI skipped.

DOI: [10.1109/TSE.2019.2897300](https://doi.org/10.1109/TSE.2019.2897300){:target="_blank"}
