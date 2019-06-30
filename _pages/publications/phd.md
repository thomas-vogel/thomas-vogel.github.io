---
title: Model-Driven Engineering of Self-Adaptive Software
permalink: publications/phd.html
layout: paper
---

## Reference
Thomas Vogel. "Model-Driven Engineering of Self-Adaptive Software". PhD Thesis, University of Potsdam, Germany, 2018.

Graded _summa cum laude_.

Reviewers: Prof. Holger Giese (University of Potsdam, Germany), Prof. Betty H.C. Cheng (Michigan State University, USA), Prof. Samuel Kounev (University of Wuerzburg, Germany).

(Submitted on 30.01.2017, defended on 19.03.2018, published online on 23.04.2018)

## Links
[Publication at the University of Potsdam (open access)](https://nbn-resolving.org/urn:nbn:de:kobv:517-opus4-409755){:target="_blank"}

[Direct access to the PDF (open access)](https://publishup.uni-potsdam.de/files/40975/diss_vogel.pdf){:target="_blank"}


## Abstract
The development of self-adaptive software requires the engineering of an adaptation engine that controls the underlying adaptable software by a feedback loop. State-of-the-art approaches prescribe the feedback loop in terms of numbers, how the activities (e.g., monitor, analyze, plan, and execute (MAPE)) and the knowledge are structured to a feedback loop, and the type of knowledge. Moreover, the feedback loop is usually hidden in the implementation or framework and therefore not visible in the architectural design. Additionally, an adaptation engine often employs runtime models that either represent the adaptable software or capture strategic knowledge such as reconfiguration strategies. State-of-the-art approaches do not systematically address the interplay of such runtime models, which would otherwise allow developers to freely design the entire feedback loop.

This thesis presents ExecUtable RuntimE MegAmodels (EUREMA), an integrated model-driven engineering (MDE) solution that rigorously uses models for engineering feedback loops. EUREMA provides a domain-specific modeling language to specify and an interpreter to execute feedback loops. The language allows developers to freely design a feedback loop concerning the activities and runtime models (knowledge) as well as the number of feedback loops. It further supports structuring the feedback loops in the adaptation engine that follows a layered architectural style. Thus, EUREMA makes the feedback loops explicit in the design and enables developers to reason about design decisions.

To address the interplay of runtime models, we propose the concept of a runtime megamodel, which is a runtime model that contains other runtime models as well as activities (e.g., MAPE) working on the contained models. This concept is the underlying principle of EUREMA. The resulting EUREMA (mega)models are kept alive at runtime and they are directly executed by the EUREMA interpreter to run the feedback loops. Interpretation provides the flexibility to dynamically adapt a feedback loop. In this context, EUREMA supports engineering self-adaptive software in which feedback loops run independently or in a coordinated fashion within the same layer as well as on top of each other in different layers of the adaptation engine. Moreover, we consider preliminary means to evolve self-adaptive software by providing a maintenance interface to the adaptation engine.

This thesis discusses in detail EUREMA by applying it to different scenarios such as single, multiple, and stacked feedback loops for self-repairing and self-optimizing the mRUBiS application. Moreover, it investigates the design and expressiveness of EUREMA, reports on experiments with a running system (mRUBiS) and with alternative solutions, and assesses EUREMA with respect to quality attributes such as performance and scalability.

The conducted evaluation provides evidence that EUREMA as an integrated and open MDE approach for engineering self-adaptive software seamlessly integrates the development and runtime environments using the same formalism to specify and execute feedback loops, supports the dynamic adaptation of feedback loops in layered architectures, and achieves an efficient execution of feedback loops by leveraging incrementality.

## BibTeX

<div class="bibtex">
<pre>@phdthesis{vogel_thesis,
  author = {Thomas Vogel},
  title = {Model-Driven Engineering of Self-Adaptive Software},
  school = {University of Potsdam, Germany},
  year = {2018}
}</pre>
</div>
