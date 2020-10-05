---
title: Bet and Run for Test Case Generation
permalink: publications/2020-SSBSEb.html
layout: page
---

## Reference
Sebastian Müller, Thomas Vogel, and Lars Grunske. "Bet and Run for Test Case Generation". In: 12th Symposium on Search-Based Software Engineering. SSBSE '20. Springer, 2020, pp. 204--219. DOI: 10.1007/978-3-030-59762-7_15.

## Links
* [Open access version](https://arxiv.org/abs/2008.01172){:target="_blank"}
* [Paper at SpringerLink](https://doi.org/10.1007/978-3-030-59762-7_15){:target="_blank"}
* [Artifact/Code](https://www.doi.org/10.5281/zenodo.3903206){:target="_blank"}

## Abstract
Anyone working in the technology sector is probably familiar with the question: "Have you tried turning it off and on again?", as this is usually the default question asked by tech support. Similarly, it is known in search-based testing that metaheuristics might get trapped in a plateau during a search. As a human, one can look at the gradient of the fitness curve and decide to restart the search, so as to hopefully improve the results of the optimization with the next run. Trying to automate such a restart, it has to be programmatically decided whether the metaheuristic has encountered a plateau yet, which is an inherently difficult problem. To mitigate this problem in the context of theoretical search problems, the Bet and Run strategy was developed, where multiple algorithm instances are started concurrently, and after some time all but the single most promising instance in terms of fitness values are killed. In this paper, we adopt and evaluate the Bet and Run strategy for the problem of test case generation. Our work indicates that use of this restart strategy does not generally lead to gains in the quality metrics, when instantiated with the best parameters found in the literature.

## BibTeX

<div class="bibtex">
<pre>@InProceedings{2020-SSBSEb,
 author = {Müller, Sebastian and Vogel, Thomas and Grunske, Lars},
 title = {Bet and Run for Test Case Generation},
 year = {2020},
 booktitle = {12th International Symposium on Search-Based Software Engineering},
 series = {SSBSE~'20},
 publisher = {Springer},
 pages = {204--219},
 doi = {10.1007/978-3-030-59762-7_15},
 note = {(accepted)},
}</pre>
</div>
