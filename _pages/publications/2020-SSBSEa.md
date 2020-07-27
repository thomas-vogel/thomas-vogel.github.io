---
title: Evolutionary Grammar-Based Fuzzing
permalink: publications/2020-SSBSEa.html
layout: page
---

## Reference
Martin Eberlein, Yannic Noller, Thomas Vogel, and Lars Grunske. "Evolutionary Grammar-Based Fuzzing". In: 12th International Symposium on Search-Based Software Engineering. SSBSE '20. Springer, 2020, _(accepted)_.

## Links
* [Artifact/Code](https://doi.org/10.5281/zenodo.3961374){:target="_blank"}

## Abstract
A fuzzer provides randomly generated inputs to a targeted software to expose erroneous behavior. To efficiently detect defects, generated inputs should conform to the structure of the input format and thus, grammars can be used to generate syntactically correct inputs. In this context, fuzzing can be guided by probabilities attached to competing rules in the grammar, leading to the idea of probabilistic grammar-based fuzzing. However, the optimal assignment of probabilities to individual grammar rules to effectively expose erroneous behavior for individual systems under test is an open research question. In this paper, we present EvoGFuzz, an evolutionary grammar-based fuzzing approach to optimize the probabilities to generate test inputs that may be more likely to trigger exceptional behavior. The evaluation shows the effectiveness of EvoGFuzz in detecting defects compared to probabilistic grammar-based fuzzing (baseline). Applied to ten real-world applications with common input formats (JSON, JavaScript, or CSS3), the evaluation shows that EvoGFuzz achieved a significantly larger median line coverage for all subjects by up to 48\% compared to the baseline. Moreover, EvoGFuzz managed to expose 11 unique defects, from which five have not been detected by the baseline.


## BibTeX

<div class="bibtex">
<pre>@inproceedings{2020-SSBSEa,
 author = {Eberlein, Martin and Noller, Yannic and Vogel, Thomas and Grunske, Lars},
 title = {Evolutionary Grammar-Based Fuzzing},
 year = {2020},
 booktitle = {12th International Symposium on Search-Based Software Engineering},
 series = {SSBSE~'20},
 publisher = {Springer},
 pages = {},
 doi = {},
 note = {(accepted)},
}</pre>
</div>
