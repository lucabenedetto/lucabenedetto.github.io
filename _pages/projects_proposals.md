---
layout: archive
title: "Project proposals"
permalink: /project_proposals/
author_profile: true
---

{% include base_path %}

Below you can find some project proposals.
Feek free to email me to discuss any of the suggestions below, or any ideas that fit with my research interests.

Graph neural networks for knowledge tracing
======
In education, knowledge tracing is the task of modelling students’ knowledge level and how it evolves over time. 
Originally performed with psychometrics approaches, such as Item Response Theory, in recent years it witnessed the application of neural networks (e.g. DKT [1]) and Transformers (e.g. [2, 3]). 
Some research also employed Graph neural networks for the task, modelling students and questions as nodes and students’ answers as edges [4].
The goal of this project is building a knowledge tracing model that leverages a graph-like structure that contains not only information about students, questions, and their interactions, but also a taxonomy of the topics assessed by the questions, the reasoning types required by them, and their textual content.

Public datasets are available:
* AI2 Reasoning Challenge (ARC) 2018 ([link](https://allenai.org/data/arc))
* NeurIPS 2020 Education Challenge ([link](https://competitions.codalab.org/competitions/25449))
A private industrial dataset might be available for this task, in case of promising results on the public dataset.

References:
* [[1](https://proceedings.neurips.cc/paper/2015/file/bac9162b47c56fc8a4d2a519803d51b3-Paper.pdf)] Deep Knowledge Tracing, NeurIPS 2015
* [[2](https://link.springer.com/chapter/10.1007/978-3-030-52240-7_46)] Deep Knowledge Tracing with Transformers, AIED 2020
* [[3](https://eric.ed.gov/?id=ED599186)] A Self-Attentive Model for Knowledge Tracing, EDM 2019
* [[4](https://link.springer.com/chapter/10.1007/978-3-030-67658-2_18)] GIKT: A Graph-Based Interaction Model for Knowledge Tracing, ECML PKDD 2020

