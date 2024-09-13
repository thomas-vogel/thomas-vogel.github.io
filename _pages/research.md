---
title: Research
permalink: research.html
layout: page
---

My research focuses on developing methods and techniques that support **engineering autonomous software systems**, especially systems that adapt themselves and impact the environment based on automated decisions (cf. **self-aware and self-adaptive software systems**). This particularly includes methods and techniques for the **quality assurance and explanations of autonomous behavior** to make such systems **trustworthy**.
In my work, I combine software engineering research with
artificial and computational intelligence,
formal methods,
control theory,
and
model-driven engineering.

My Ph.D. research was about the [_Model-Driven Engineering of Self-Adaptive Software_](publications/phd) where models and model-driven engineering techniques are exceedingly leveraged at run-time to achieve a higher degree of flexibility in the design, evolution, and operation of such software systems than the state of the art with code-based solutions (cf. [EUREMA](projects/#phd-projects) and [MORISIA](projects/#phd-projects) projects).

In my postdoctoral studies I broadened my research along three lines, which inspire and benefit from each other:

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

### (2) Explaining intelligent methods and making intelligent methods self-adaptive
Methods from computational and artificial intelligence are typically black-box and arcane for software engineers, which impedes an understanding why such intelligent methods work well and others do not for a specific problem. My goal is to develop explanations that enable such an understanding, and I particularly use _software engineering tools_ such as test case generators as target systems that use intelligent methods (e.g., evolutionary algorithms).

With the [FLASH](projects) project, I developed **explanations of the difficulty of optimization problems in search-based software engineering** based on a fitness landscape analysis. The explanations enable a better understanding of the search problems and intelligent methods, which helps in manually configuring a method to yield better results for a specific problem. In this context, I envision **self-adaptive intelligent methods** that automatically and dynamically configure themselves at run-time.

As an example, I developed analytical explanations of the difficulty of generating test cases for mobile apps with _Sapienz_ and devised an ad-hoc solution for a _self-adaptive Sapienz_ that achieves better or ar least similar test results ([SSBSE'19](publications/2019-SSBSE), [IST'21](publications/2020-IST), project [_Self-Adaptive Search for Sapienz_](projects)).

The goal of the recent project [_Controlling Search-Based Test Case Generation and Program Repair_](projects/flash2) is to systematically develop controlled (self-adaptive) solutions for test case generation and program repair based on dynamic features identified in an evolution analysis.

Since the techniques to develop explanations are generic, they can be also applied to optimization problems in autonomous software systems such as finding optimal adaptation decisions and system configurations.

Besides aiming for a better understanding of intelligent methods, I am interesting in developing and applying such methods to software engineering problems such as testing ([SSBSE'20b](publications/2020-SSBSEb)), fuzzing ([SSBSE'20a](publications/2020-SSBSEa)), and vulnerability detection ([IST'22b](publications/2022-ISTb)).

### (3) Practical and explainable verification of software systems
Given the increasing level of autonomy, large configuration spaces, or uncertainty of software systems, assuring such systems has become a major challenge ([SEfSAS'17a](publications/2017-SEFSAS3a), [SE4Science'19](publications/2019-SE4Science)). The use of formal methods (e.g., model checking), and the interpretation of the results of such methods (e.g., a counterexample) are often difficult, error-prone, and costly. My goal is to make such methods practically usable, for instance, by:
* following a model-based approach to tame the complexity of safety analysis ([IMBSA'19](publications/2019-IMBSA))
* leveraging natural language-based property specification patterns ([IST'22c](publications/2022-ISTc))
* improving the explainability and interpretation of counterexamples ([EMSE'23](publications/2023-EMSE), [IST'22a](publications/2022-ISTa), [ICSME-RR'21](publications/2021-ICSME-RR), [IMBSA'20](publications/2020-IMBSA))
* automatically deriving verifiable models from higher-level user input such as goal models ([SEAMS'19](publications/2019-SEAMS))
