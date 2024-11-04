---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

**Authentication Logging to a Public Blockchain**
<br>_Advisor: Professor David Mazieres_
<br>_Winter 2023–Present_
<br>We are developing a new authentication logging protocol with the improved security guarantees from the Larch universal login system that (1) it does not require a trusted third party to run a log server and (2) users have security even when their log server and a relying party are colluding. _Recipient of the IORH Blockchain Grant._

**Sparse Polynomial Commitment Scheme from LaBRADOR**
<br>_Advisor: Professor Dan Boneh_
<br>_Winter 2023—Present_
<br>We are building a sparse polynomial commitment scheme from the LaBRADOR compact proof system, with applications to building post-quantum Lasso lookup arguments.

<img width="402" alt="Screenshot 2024-11-04 at 15 45 32" src="https://github.com/user-attachments/assets/1bbb1e7c-8f52-4457-8808-c339f7f44736">**Faster Fully Homomorphic Operations for Deep Circuits [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3626232.3653277) [(Code)](https://github.com/ihyunnam/Avg-Act-Swap)**
<br>_Advisor: Professor John Mitchell_
<br>_Summer 2023–Spring 2024_
<br>I developed the Avg-Act Swap, a simple technique to place an AvgPool before an activation function for faster encrypted inference speed for machine learning on fully homomorphically encrypted (FHE) data. I designed and implemented two FHE-friendly DNNs that achieved at most 30% increase in encrypted inference speed when used with the Avg-Act Swap; and modified Lenet-5 with the Avg-Act Swap to achieve a 27% increase in encrypted inference speed and a 90% accuracy. Furthermore, I proposed the first formalized plaintext overflow detection method in floating-point arithemetic FHE schemes and proved IND-CPA. _Paper published in the Proceedings of the 14th ACM Conference on Data and Application Security and Privacy._

<img width="426" alt="Screenshot 2024-11-04 at 15 46 35" src="https://github.com/user-attachments/assets/cee39bbb-a101-45da-9a17-6b4035fc2941">**Identifying TLS Clients Using Unsupervised Learning on Domain Names [(Preprint)](https://arxiv.org/pdf/2410.02040) [(Code)](https://github.com/ihyunnam/clid)**
<br>_Advisor: Professor Zakir Durumeric_
<br>_Winter 2023–Summer 2023_
<br>Many existing rule-based TLS client identification tools rely on outdated databases and are unable to identify a wide range of clients in real-world networks. I proposed to build Clid, a new client identification tool that uses unsupervised learning on domain names from the server name indication field. Clid uses Bayesian optimization and DBSCAN clustering to map clients to domain names that are most informative of their identity, as a first step to helping researchers and operators understand network clients. I showed with experiments that Clid is able to identify 'strongly associated' domain names for at least 60% of all clients in randomly sampled TLS connections.

<img width="144" alt="Screenshot 2024-11-04 at 15 43 16" src="https://github.com/user-attachments/assets/3f216bf4-7d17-4cc0-85c5-d7f2b33e45c1">**Shuffle Squares and Reverse Shuffle Squares [(Paper)](https://arxiv.org/pdf/2109.12455)**
<br>_Advisor: Dr. Pawel Grzegrzolka_
<br>_Summer 2021–Fall 2021_
<br>In a team of four, we proved a conjecture from 2012 on enumerating shuffle squares (words containing disjoint identical strings) and disproved a companion conjecture on reverse shuffle squares. These findings contributed to efficient error-correcting codes for deletion channels. _Paper published in the European Journal of Combinatorics (Vol 116)._
