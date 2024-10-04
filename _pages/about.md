---
permalink: /
title: 
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Master's student in Computer Science at Stanford University. I am intersted in building secure systems with cryptography that has real-life applications.

I am very fortunate to be advised by professors [Dan Boneh](https://crypto.stanford.edu/~dabo/), [David Mazieres](https://www.scs.stanford.edu/~dm/), and [John Mitchell](https://theory.stanford.edu/people/jcm/). I received my B.S. with [Honors](/files/honors.pdf) in Computer Science on the Systems track and B.S. in Mathematics from Stanford University in June 2024.

<span style="color: red;">I am currently applying for Ph.D. programs in Computer Science for the fall 2025 entry term.</span>

Here is my [CV](/files/cv.pdf).

Research
------
**Authentication Logging to a Public Blockchain**
<span style="font-size: 15px;"><br>_Advisor: Professor David Mazieres_
<br>_Winter 2023–Present_
<br>_(In progress)_ We are developing a new authentication logging protocol with the improved security guarantees from the Larch universal login system that (1) it does not require a trusted third party to run a log server and (2) users have security even when their log server and a relying party are colluding.</span>

**Lasso Over Lattices**
<span style="font-size: 15px;"><br>_Advisor: Professor Dan Boneh_
<br>_Winter 2023–Present_
<br>_(In progress)_ We are building Lasso lookup arguments on lattices, in contrast to the original scheme that works on field elements.</span>

**Faster Fully Homomorphic Operations Applications For Machine Learning on Encrypted Data**
<span style="font-size: 15px;"><br>_Advisor: Professor John Mitchell_
<br>_Summer 2023–Spring 2024_
<br>I developed the Avg-Act Swap, a simple technique to place an AvgPool before an activation function for faster encrypted inference speed for machine learning on fully homomorphically encrypted (FHE) data. I designed and implemented two FHE-friendly DNNs that achieved at most 30% increase in encrypted inference speed when used with the Avg-Act Swap; and modified Lenet-5 with the Avg-Act Swap to achieve a 27% increase in encrypted inference speed and a 90% accuracy. Furthermore, I proposed the first formalized plaintext overflow detection method in floating-point arithemetic FHE schemes and proved IND-CPA.</span>

**Identifying TLS Clients Using Unsupervised Learning on Domain Names**
<span style="font-size: 15px;"><br>_Advisor: Professor Zakir Durumeric_
<br>_Winter 2023–Summer 2023_
<br>Many existing rule-based TLS client identification tools rely on outdated databases and are unable to identify a wide range of clients in real-world networks. I proposed to build Clid, a new client identification tool that uses unsupervised learning on domain names from the server name indication field. Clid uses Bayesian optimization and DBSCAN clustering to map clients to domain names that are most informative of their identity, as a first step to helping researchers and operators understand network clients. I showed with experiments that Clid is able to identify 'strongly associated' domain names for at least 60% of all clients in randomly sampled TLS connections.</span>

**Shuffle Squares and Reverse Shuffle Squares**
<span style="font-size: 15px;"><br>_Advisor: Dr. Pawel Grzegrzolka_
<br>Summer 2021–Fall 2021_
<br>In a team of four, we proved a conjecture from 2012 on enumerating shuffle squares (words containing disjoint identical strings) and disproved a companion conjecture on reverse shuffle squares. These findings contributed to efficient error-correcting codes for deletion channels.</span>

Publications
------
**The Avg-Act Swap and Plaintext Overflow Detection in Homomorphic Operations Over Deep Circuits** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3626232.3653277) [[code]](https://github.com/ihyunnam/Avg-Act-Swap)
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Ihyun Nam
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CODASPY 2024

**Shuffle Squares and Reverse Shuffle Squares**[[paper]](https://pdf.sciencedirectassets.com/272420/1-s2.0-S0195669823X00079/1-s2.0-S0195669823002019/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEID%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCID0bKPQNxvp94mwkosn%2F7rx8sDLuXQaFqkhfXXJXAg6sAiEAgIemgjCp8TeWTcGID9ZdP%2FhO9SrPjSg8dzgeUwTy4LwquwUIyf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDNRI012SD7tos9i7CiqPBStFTwRjGH5zUKgB1cBnbqsuv53Zg3gxrVx7hjM9zJkpAlm%2F%2BUk8eABasvbf3ZKjVW9JfilYXyw4AW1cNiZ06kY%2FsCb2aPb4tVqX9ZzgOLzC3ZzAnPn2XXyDv1y%2FIYuUUWn9vtVuSYMbPfiOYtrbVKeaWRjF%2FslbDtnyJPSQhrrrw068KKvmLmdR4tUuDA96haR2d3KnPfGZ%2BI4czOAXe19hUUhIbLXYZnbs2%2BFRi1vVYEVVCc78jXGGGca1NCBxYkymYsyvlNCrzA8HD%2Fhd39vfnyExta7Mr%2B3VTtks3QvCsShpPW%2F5XsIGC7uZSNPXTItb0R8vk1ACbX0G3hRWUorQXAef4NzMhBlvua%2BQ9vduU4HJfJXiwwJ5FqUQC0TSRAio6%2Fy0Eu187JOa0OpqPhWbDE9lg6Oke5eQGkiWSmAaM55sarmVyktjIzBtlC5RE%2BQfFP7yAmDg6TCc2xszaol9tpC73CGmWrFCOdnK5nSjKt4%2Fidg%2B8yfIqlZnC%2FUEq9mg9W5QQqHoYQuK60QRquveXQGGTv7bbF9eOYFw9wbUeiL4M%2B%2BuV8oCY%2Bi38GZ316kzmcNmVak2vXQ3yucntsWj9mW4d46ZRyIeqADUZoE08H87Ov%2BgBy5IjXxG0kB7NJ4iSIwsVauy89SDAiqFUtFqlDgJe0K4dv6yX8WPSDJsm6FsFs4kapGW2u0oLSLuceTHiHvQq3z1EVXAEdBRHaFxEG57lfF%2BR%2FrF0JaZhmxCQyIrFH%2BNmDUwema69ZUwkzJcs0nLNI7antAYHIsEwkWkbmdDmy0esSTH2ggc7RlNsczyuc0R0CfWCY1S45h70lXG4TY9hWNvarizW1zXfsjtcQBiq0DOWKej%2Fy8SqMww2d78twY6sQFLrRBFL%2B1WbDt0LVBx0TB%2B8pwuOKPkqLb%2BwzP28OTGHw2DvHM15t8CDgKVajbedte0tyKpbDWgLmRfzou8J0%2B9Sz3vUAw1YzbxWmvA28G12fHlSkZhT8v67yRHq%2BVUHeFw6ZH6eKvkFN%2B%2FzZv%2BSsWFr7CfVwfjEvwLCsXsxFY2ymWwFCxifp4675dJ2vqpvljpBoqoCbAWYh1pbL9YRjx0cySz%2Bfy%2BombnOhkxXNuMOdg%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20241004T005649Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYSIRJC5A2%2F20241004%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b99419d4c139f49d976d20301983bf724ae0e78b169ab8a96df421f6f0afd9ea&hash=bc2c052aeb7171d4467a60aec96cd1e75557dd780666fb2fcb353270f6ba7f9d&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0195669823002019&tid=spdf-2d06e26e-bea6-4448-8cec-27a3162605aa&sid=c0d810a07f18b9460788338-69cdd54e306agxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=10145d06035156540b03&rr=8cd136da6b72cf2f&cc=us)
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Xiaoyu He*, Emily Huang*, Ihyun Nam*, Rishubh Thaper*
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The European Journal of Combinatorics (Vol 116)

**Clid: Identifying TLS Clients With Unsupervised Learning on Domain Names** [[paper]](https://arxiv.org/pdf/2410.02040) [[code]](https://github.com/ihyunnam/clid)
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Ihyun Nam, Gerry Wan
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Posted on arXiv (2024)

**A Survey of Multivariate Polynomial Commitment Schemes** [[paper]](https://arxiv.org/pdf/2306.11383)
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Ihyun Nam
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Posted on arXiv (2023)

Presentations
------
<b>"The Avg-Act Swap and Plaintext Overflow Detection in Homomorphic Operations Over Deep Circuits"</b>
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The 14th ACM Conference on Data and Application Security and Privacy (Porto, Portugal): June 2024

<b>"The Avg-Act Swap: Towards Faster Machine Learning Applications of Fully Homomorphic Encryption"</b>
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Symposia for Undergraduate Research and Public Service (Stanford, CA): October 2023

<b>"Shuffle Squares and Reverse Shuffle Squares"</b>
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Symposia for Undergraduate Research and Public Service (Stanford, CA): October 2022

Grants and Awards
------
[The Hoefer Prize for Writing in the Major](https://pwr.stanford.edu/hoefer-prize-essays-archive) (Spring 2024)
<br>[Conference Scholarship for the Richard Tapia Conference](https://tapiaconference.cmd-it.org/) (Summer 2023)
<br>[Major Grant](https://undergradresearch.stanford.edu/fund-your-project/explore-student-grants/major) (Summer 2023)
<br>[Talent Award of Korea](https://en.wikipedia.org/wiki/Talent_Award_of_Korea) (Winter 2022)
<br>Presidential Science Scholarship of Korea (2020-24)

Teaching
------
[Math 19: Calculus](https://explorecourses.stanford.edu/search?q=MATH19) - Teaching Assistant (Fall 2024)
<br>[INTLPOL 268: Hack Lab](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&page=0&catalog=&q=INTLPOL%20268%3A%20Hack%20Lab%3A%20Introduction%20to%20Cybersecurity&collapse=) - Lab Teaching Assistant (Fall 2023)
<br>[Stanford University Mathematics Camp](https://sumac.spcs.stanford.edu/) - Teaching Assistant and Residential Counselor (Summer 2023)

Service
------
[Stanford Women in Math Mentoring](https://swimm.stanford.edu/) - Board Member (2023-24); Mentee (2020-23)
<br>[Stanford Womens Community Center](https://wcc.stanford.edu/) - Community Outreach Intern (2020-21)
<br>[Stanford Math Tournament](https://sumo.stanford.edu/smt.html) - Problem Writer (2020-21)

Contact
------
Reach me at ihyun [at] stanford [dot] edu.
