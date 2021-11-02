---
title: "Towards Using Package Centrality Trend to Identify Packages in Decline"
paper_id: Mujahid_TEM2021
collection: publications
authors: "Suhaib Mujahid, Diego Elias Costa, Rabe Abdalkareem, Emad Shihab, Mohamed Aymen Saied, Bram Adams"
permalink: /publication/2021-10-Mujahid-TEM
date: 2021-10-18
venue: "	IEEE Transactions on Engineering Management Journal (TEM) - Special Issue on Collaboration and Innovation Dynamics in Software Ecosystems"
series: "TEM&apos;21"
preprint: "/papers/Mujahid_TEM2021.pdf"
paperurl: "https://arxiv.org/abs/2107.10168"
---

**Abstract:** Due to their increasing complexity, today's software systems are frequently built by leveraging reusable code in the form of libraries and packages. Software ecosystems (e.g., npm) are the primary enablers of this code reuse, providing developers with a platform to share their own and use others' code. These ecosystems evolve rapidly: developers add new packages every day to solve new problems or provide alternative solutions, causing obsolete packages to decline in their importance to the community. Developers should avoid depending on packages in decline, as these packages are reused less over time and may become less frequently maintained. However, current popularity metrics (e.g., Stars, and Downloads) are not fit to provide this information to developers because their semantics do not aptly capture shifts in the community interest.

In this paper, we propose a scalable approach that uses the package's centrality in the ecosystem to identify packages in decline. We evaluate our approach with the npm ecosystem and show that the trends of centrality over time can correctly distinguish packages in decline with an ROC-AUC of 0.9. The approach can capture 87% of the packages in decline, on average 18 months before the trend is shown in currently used package popularity metrics. We implement this approach in a tool that can be used to augment the npms metrics and help developers avoid packages in decline when reusing packages from npm.

DOI: [10.1109/TEM.2021.3122012](https://arxiv.org/abs/2107.10168){:target="\_blank"}
