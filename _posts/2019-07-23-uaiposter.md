---
title: "Publication: A Tighter Analysis of Randomised Policy Iteration"
tags:
  - Publication
  - IIT Bombay
  - Research
---

#### Authors: Meet Taraviya, Shivaram Kalyanakrishnan

*In Proceedings of the 35th Conference on Uncertainty in Artificial Intelligence (UAI 2019)*

Policy Iteration (PI) is a popular family of algorithms to compute an optimal policy for a given Markov Decision Problem (MDP). Starting from an arbitrary initial policy, PI repeatedly performs locally-improving switches until an optimal policy is found. The exact form of the switching rule gives rise to different variants of PI. Two decades ago, Mansour and Singh [1999] provided the first non-trivial upper bound on the number of iterations taken by “Howard’s PI” (HPI), a widely-used variant of PI. They also proposed a randomised variant (RPI) with an even tighter upper bound. Their bounds for HPI and RPI have not been improved subsequently, although curiously, these algorithms tend to perform much better in practice than theoretically-superior variants.

We revisit the algorithms and analysis of Mansour and Singh [1999]. We prove a novel result on the structure of the policy space for *k*-action MDPs, k≥2, which generalises a result known for *k=2*. Also proposing a new counting argument, we obtain a bound of *(O((k logk)^0.5))^n* iterations for an algorithm akin to RPI, improving significantly upon Mansour and Singh’s original bound of roughly *O((k/2)^n)*. Similar analysis of a randomised variant of HPI also yields an upper bound of *(O((k logk)^0.5))^n* iterations, registering the first exponential improvement for HPI over the trivial bound of *k^n* . Our other contributions include a lower bound of *Ω(n)* iterations for RPI and an upper bound of *1.6001^n* iterations for a randomised variant of "BatchSwitching PI" [Kalyanakrishnan et al., 2016a] on *2*-action MDPs—the tightest upper bound shown yet for the PI family.

#### References:

* [Howard, 1960] Ronald A. Howard. *Dynamic programming and Markov processes.* MIT Press, 1960.
* [Mansour and Singh, 1999] Yishay Mansour and Satinder Singh. *On the complexity of policy iteration.* In Proceedings of the Fifteenth Conference on Uncertainty in Artificial Intelligence (UAI 1999), pages401–408. Morgan Kaufmann, 1999.
* [Kalyanakrishnan et al., 2016a] Shivaram Kalyanakrishnan, Utkarsh Mall, and Ritish Goyal. *Batch-switching policy iteration.* In Proceedings of the Twenty-fifth International Joint Conference on Artificial Intelligence (IJCAI 2016), pages 3147–3153. AAAI Press, 2016.

#### Resources:

* [Full paper](https://meettaraviya.github.io/pdfs/174.pdf "A Tighter Analysis of Randomised Policy Iteration")
* [Poster presentation](https://meettaraviya.github.io/pdfs/UAI_2019_poster.pdf "A Tighter Analysis of Randomised Policy Iteration - Poster")

