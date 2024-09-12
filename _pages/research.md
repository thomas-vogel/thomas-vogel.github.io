---
title: Research
permalink: research.html
layout: page
---

My research focuses on developing methods and techniques that support **engineering,  assuring, and understanding autonomous software systems**, especially systems that adapt themselves and impact the environment based on automated decisions (cf. **self-aware and self-adaptive software systems**).
In my work, I combine software engineering research with
artificial and computational intelligence,
formal methods,
control theory,
and
model-driven engineering.

My Ph.D. research was about the [_Model-Driven Engineering of Self-Adaptive Software_](publications/phd) where models and model-driven engineering techniques are exceedingly leveraged at run-time to achieve a higher degree of flexibility in the design, evolution, and operation of such software systems than the state of the art with code-based solutions (cf. [EUREMA](#projects) and [MORISIA](#projects) projects).

In my postdoctoral studies I broadened my research along three lines:

### (1) Methods and techniques to achieve and cope with the increasing level of autonomy of software systems
We aim for an increasing level of autonomy of software systems, which enables them to  operate in uncertain and dynamic environments (e.g., cyber-physical systems that autonomously adapt themselves to changing environmental conditions). This requires novel means to engineer such self-adaptive systems.
In this context, I research methods and techniques from
computational and artificial intelligence,
formal methods,
control theory,
software quality assurance,
and
software architecture and design
to increase as well as cope with the autonomous behavior of software systems:

* **Learning and optimization from computational and artificial intelligence** to automatically identify optimal system configurations, adaptation rules, and adaptation decisions under uncertainty, which increases the level of autonomy ([TAAS'20](publications/2020-TAAS), [SEAMS'20a](publications/2020-SEAMSa), [SASO'19](publications/2019-SASO), [SEAMS'18b](publications/2018-SEAMSb), [ICAC'17](publications/2017-ICAC)), and to generate explanations for property violations in cyber-physical systems ([IEEE Software'24](publications/2024-IEEESoftware))
* **Synthesis and model checking from formal methods** to generate optimal controllers for adaptation decisions with guarantees ([SEAMS'24](publications/2024-SEAMS)) and to formally verify self-adaptive systems ([SEAMS'19](publications/2019-SEAMS), [SEAMS'18b](publications/2018-SEAMSb))
* **Control-theoretical principles** to systematically engineer self-adaptive systems with guarantees ([SEAMS'20a](publications/2020-SEAMSa), [SEAMS'20b](publications/2020-SEAMSb), [TAAS'17](publications/2017-TAAS), [CASaS'17](publications/2017-CASaS), [SEAMS'15](publications/2015-SEAMS))
* **Verification and testing from software quality assurance** techniques to verify and validate self-adaptive systems ([SEAMS'23a](publications/2023-SEAMSa), [SEAMS'19](publications/2019-SEAMS), [SEAMS'18b](publications/2018-SEAMSb), [SEfSAS'17a](publications/2017-SEFSAS3a), [SEfSAS'17b](publications/2017-SEFSAS3b), [SASOW'15](publications/2015-SASOW))
* **Developing architecture and design principles** for self-aware/self-adaptive systems  (see [ACSOSC'20](publications/2020-ACSOSC), [SACS'17a](publications/2017-SACSa), [SACS'17b](publications/2017-SACSb), [SACS'17c](publications/2017-SACSc))

<BR />
Additionally, I am promoting rigor evaluation of self-adaptive software systems research ([SEAMS'21](publications/2021-SEAMS)) and industry-relevant research in this area ([SEAMS'23b](publications/2023-SEAMSb), [SIGSOFT SEN'22](publications/2022-SEN)), for instance, using artifacts such as _mRUBiS_ ([SEAMS'18a](publications/2018-SEAMSa)).

### (2) Understanding intelligent methods and making intelligent methods self-adaptive
Methods from computational and artificial intelligence are typically black-box and arcane for software engineers, which impedes an understanding why such intelligent methods work well and others do not for a specific problem. My goal is to develop explanations that enable such an understanding, and I particularly use _software engineering tools_ such as test case generators as target systems that use intelligent methods (e.g., evolutionary algorithms).

With the [FLASH](#projects) project, I developed **explanations of the difficulty of optimization problems in search-based software engineering** based on a fitness landscape analysis. The explanations enable a better understanding of the search problems and intelligent methods, which helps in manually configuring a method to yield better results for a specific problem. In this context, I envision **self-adaptive intelligent methods** that automatically and dynamically configure themselves at run-time.

As an example, I developed analytical explanations of the difficulty of generating test cases for mobile apps with _Sapienz_ and devised an ad-hoc solution for a _self-adaptive Sapienz_ that achieves better or ar least similar test results ([SSBSE'19](publications/2019-SSBSE), [IST'21](publications/2020-IST), project [_Self-Adaptive Search for Sapienz_](#projects)).

The goal of the recent project [_Controlling Search-Based Test Case Generation and Program Repair_](projects/flash2) is to systematically develop controlled (self-adaptive) solutions for test case generation and program repair based on dynamic features identified in an evolution analysis.

Since the techniques to develop explanations are generic, they can be also applied to optimization problems in autonomous software systems such as finding optimal adaptation decisions and system configurations.

Besides aiming for a better understanding of intelligent methods, I am interesting in developing and applying such methods to software engineering problems such as testing ([SSBSE'20b](publications/2020-SSBSEb)), fuzzing ([SSBSE'20a](publications/2020-SSBSEa)), and vulnerability detection ([IST'22b](publications/2022-ISTb)).

### (3) Practical and explainable verification of software systems
Given the increasing level of autonomy, large configuration spaces, or uncertainty of software systems, assuring such systems has become a major challenge ([SEfSAS'17a](publications/2017-SEFSAS3a), [SE4Science'19](publications/2019-SE4Science)). The use of formal methods (e.g., model checking), and the interpretation of the results of such methods (e.g., a counterexample) are often difficult, error-prone, and costly. My goal is to make such methods practically usable, for instance, by:
* following a model-based approach to tame the complexity of safety analysis ([IMBSA'19](publications/2019-IMBSA))
* leveraging natural language-based property specification patterns ([IST'22c](publications/2022-ISTc))
* improving the explainability and interpretation of counterexamples ([EMSE'23](publications/2023-EMSE), [IST'22a](publications/2022-ISTa), [ICSME-RR'21](publications/2021-ICSME-RR), [IMBSA'20](publications/2020-IMBSA))
* automatically deriving verifiable models from higher-level user input such as goal models ([SEAMS'19](publications/2019-SEAMS))

<BR />

# Projects

## As Principal Investigator

### Controlling Search-Based Test Case Generation and Program Repair
Dynamically controlling search processes to improve automated test case generation and program repair using control and self-adaptation principles (funded by DFG, [project website](projects/flash2)).

### Self-Adaptive Search for Sapienz
Transferring self-adaptation principles to the search process of Sapienz, a search-based test suite generation tool for mobile applications (funded by the 2018 Facebook Testing and Verification Research Award). For further details, please have a look at the following presentation: [Search-Based App Testing, Fitness Landscape Analysis, and Diversity](https://www.tele-task.de/lecture/video/7788/){:target="_blank"}.

## As Research Assistant

### FONDA -- Foundations of Workflows for Large-Scale Scientific Data Analysis
As part of the [DFG Collaborative Research Center 1404 "FONDA -- Foundations of Workflows for Large-Scale Scientific Data Analysis"](https://fonda.hu-berlin.de/){:target="_blank"}, I contribute to two subprojects:
* **Deriving Trust Levels for Multi-Choice Data Analysis Workflows:** The goal of this subproject is to improve the dependability of data analysis workflows in computational materials science by sampling configurations of such workflows and testing based on the NOMAD repository.
* **Distributed Run-Time Monitoring and Control of Data Analysis Workflows:** The goal of this subproject is to improve the dependability of data analysis workflows by monitoring and controlling such workflows at run-time.

### FLASH: Fitness landscape analysis to improve search-based software engineering
Analyzing and understanding the search space and search methods for software engineering problems to improve state-of-the-art search
heuristics to solve these problems
(funded by DFG, [project website](https://www.informatik.hu-berlin.de/en/forschung-en/gebiete/se/research/ongoingprojects/flash){:target="_blank"}).

### Specification and Verification of Requirements and Safety Contracts
Developing a domain-specific language for specifying and verifying requirements and safety contracts in the
automotive industry, and techniques for explaining counter examples of the verification process (in cooperation with BOSCH Research).

### Safe.Spec: Quality Assurance for Requirements Specifications
Developing a user-friendly, model-driven approach to specify, compose, and verify scenario-based requirements. This includes the pattern-based specification of scenarios using sequence diagrams, composing scenarios to automaton-based specifications, and integrating natural language-based property specification patterns with UPPAAL. (in cooperation with TWT GmbH, funded by BMBF, [project website](https://www.informatik.hu-berlin.de/en/forschung-en/gebiete/se/research/ongoingprojects/safespec){:target="_blank"}).

## Ph.D. Projects

### EUREMA: Executable Runtime Megamodels
A model-driven engineering approach to specify, execute, adapt, and evolve feedback loops in self-adaptive software systems ([project website](https://www.hpi.uni-potsdam.de/giese/public/mdelab/mdelab-projects/software-engineering-for-self-adaptive-systems/eurema/){:target="_blank"}).

### MORISIA: Models at Runtime for Self-Adaptive Software
Researching runtime models for feedback loops in self-adaptive software systems to realize self-awareness and self-adaptation ([project website](https://www.hpi.uni-potsdam.de/giese/public/mdelab/mdelab-projects/software-engineering-for-self-adaptive-systems/morisia/){:target="_blank"}).

### mRUBiS: modular Rice University Bidding System
An exemplar for model-based architectural self-healing and self-optimization of an information system. See [paper](publications/2018-SEAMSa) and [artifact at GitHub](https://github.com/thomas-vogel/mRUBiS){:target="_blank"}.
