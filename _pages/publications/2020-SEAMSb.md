---
title: Towards Bridging the Gap between Control and Self-Adaptive System Properties
permalink: publications/2020-SEAMSb.html
layout: page
---

## Reference
Javier Cámara, Alessandro V. Papadopoulos, Thomas Vogel, Danny Weyns, David Garlan, Shihong Huang, and Kenji Tei. “Towards Bridging the Gap between Control and Self-Adaptive System Properties”. In: International Symposium on Software Engineering for Adaptive and Self-Managing Systems. SEAMS ’20. ACM, 2020, DOI: 10.1145/3387939.3391568, _(accepted)_.

## Links
* [Open access version](https://arxiv.org/abs/2004.11846){:target="_blank"}

## Abstract
Control theoretical techniques have been successfully adopted as methods for self-adaptive systems design to provide formal guarantees about the effectiveness and robustness of adaptation mechanisms. However, the computational effort to obtain guarantees poses severe constraints when it comes to dynamic adaptation. In order to solve these limitations, in this paper, we propose a hybrid approach combining software engineering, control theory, and AI to design for software self-adaptation. Our solution proposes a hierarchical and dynamic system manager with performance tuning. Due to the gap between high-level requirements specification and the internal knob behavior of the managed system, a hierarchically composed components architecture seek the separation of concerns towards a dynamic solution. Therefore, a two-layered adaptive manager was designed to satisfy the software requirements with parameters optimization through regression analysis and evolutionary meta-heuristic. The optimization relies on the collection and processing of performance, effectiveness, and robustness metrics w.r.t control theoretical metrics at the offline and online stages. We evaluate our work with a prototype of the Body Sensor Network (BSN) in the healthcare domain, which is largely used as a demonstrator by the community. The BSN was implemented under the Robot Operating System (ROS) architecture, and concerns about the system dependability are taken as adaptation goals. Our results reinforce the necessity of performing well on such a safety-critical domain and contribute with substantial evidence on how hybrid approaches that combine control and AI-based techniques for engineering self-adaptive systems can provide effective adaptation.

## BibTeX

<div class="bibtex">
<pre>@inproceedings{2020-SEAMSb,
    author = {Cámara, Javier and Papadopoulos, Alessandro V. and Vogel, Thomas and Weyns, Danny and Garlan, David and Huang, Shihong and Tei, Kenji},
    title = {Towards Bridging the Gap between Control and Self-Adaptive System Properties},
    year = {2020},
    booktitle = {International Symposium on Software Engineering for Adaptive and Self-Managing Systems},
    series = {SEAMS~'20},
    publisher = {ACM},
    pages = {},
    doi = {10.1145/3387939.3391568},
    note = {\textit{(accepted)}},
}</pre>
</div>
