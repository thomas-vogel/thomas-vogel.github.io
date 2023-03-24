---
title: Runtime Verification of Self-Adaptive Systems with Changing Requirements
permalink: publications/2023-SEAMSa.html
layout: page
---

## Reference
Marc Carwehl, Thomas Vogel, Genaína Nunes Rodrigues, and Lars Grunske. “Runtime Verification of Self-Adaptive Systems with Changing Requirements”. In: 18th International Symposium on Software Engineering for Adaptive and Self-Managing Systems. SEAMS '23. IEEE, 2023.

## Links
* _tba_

## Abstract
To accurately make adaptation decisions, a self-adaptive system needs precise means to analyze itself at runtime. To this end, runtime verification can be used in the feedback loop to check that the managed system satisfies its requirements formalized as temporal-logic properties. These requirements, however, may change due to system evolution or uncertainty in the environment, managed system, and requirements themselves. Thus, the properties under investigation by the runtime verification have to be dynamically adapted to represent the changing requirements while preserving the knowledge about requirements satisfaction gathered thus far, all with minimal latency. To address this need, we present a runtime verification approach for self-adaptive systems with changing requirements. Our approach uses property specification patterns to automatically obtain automata with precise semantics that are the basis for runtime verification. The automata can be safely adapted during runtime verification while preserving intermediate verification results to seamlessly reflect requirement changes and enable continuous verification. We evaluate our approach on an Arduino prototype of the Body Sensor Network and the Timescales benchmark. Results show that our approach is over five times faster than the typical approach of redeploying and restarting runtime monitors to reflect requirements changes, while improving the system's trustworthiness by avoiding interruptions of verification.

## BibTeX

<div class="bibtex">
<pre>@inproceedings{2023-SEAMSa,
  author = {Carwehl, Marc and Vogel, Thomas and Rodrigues, Genaína Nunes and Grunske, Lars},
  title = {Runtime Verification of Self-Adaptive Systems with Changing Requirements},
  year = {2023},
  booktitle = {18th International Symposium on Software Engineering for Adaptive and Self-Managing Systems},
  series = {SEAMS~'23},
  publisher = {IEEE},
  pages = {},
  doi = {},
}</pre>
</div>
