---
layout: archive
title: "Project proposals"
permalink: /project_proposals/
author_profile: true
---

{% include base_path %}

Below you can find some project proposals, both are co-supervised by myself and [Dr. Andrew Caines](https://www.cl.cam.ac.uk/~apc38/).
Feek free to email me to discuss any of the suggestions below, or any ideas that fit with my research interests.

# Graph neural networks for knowledge tracing

In education, knowledge tracing is the task of modelling students’ knowledge level and how it evolves over time. 
Originally performed with psychometrics approaches, such as Item Response Theory, in recent years it witnessed the application of neural networks (e.g. DKT [1]) and Transformers (e.g. [2, 3]). 
Some research also employed Graph neural networks for the task, modelling students and questions as nodes and students’ answers as edges [4].
The goal of this project is building a knowledge tracing model that leverages a graph-like structure that contains not only information about students, questions, and their interactions, but also a taxonomy of the topics assessed by the questions, the reasoning types required by them, and their textual content.

## Datasets:
* AI2 Reasoning Challenge (ARC) 2018 ([link](https://allenai.org/data/arc))
* NeurIPS 2020 Education Challenge ([link](https://competitions.codalab.org/competitions/25449))
* A private industrial dataset might be available for this task, in case of promising results on the public dataset.

## References:
* [[1](https://proceedings.neurips.cc/paper/2015/file/bac9162b47c56fc8a4d2a519803d51b3-Paper.pdf)] Deep Knowledge Tracing, NeurIPS 2015
* [[2](https://link.springer.com/chapter/10.1007/978-3-030-52240-7_46)] Deep Knowledge Tracing with Transformers, AIED 2020
* [[3](https://eric.ed.gov/?id=ED599186)] A Self-Attentive Model for Knowledge Tracing, EDM 2019
* [[4](https://link.springer.com/chapter/10.1007/978-3-030-67658-2_18)] GIKT: A Graph-Based Interaction Model for Knowledge Tracing, ECML PKDD 2020

# Question difficulty estimation from text with graph-structured knowledge bases

Question Difficulty Estimation (QDE) consists in estimating a numerical value, either continuous or discrete, that represents the difficulty of an exam question. 
Traditionally, it is performed with manual calibration or with pretesting, which both have some limitations: crucially manual calibration is subjective, and pretesting is slow and expensive to perform.
Recent research has targeted these limitations by proposing the usage of Natural Language Processing (NLP) techniques for QDE, with the idea that question text is the only information that is available at the time question creation and, if we were capable of performing QDE from text, we might overcome the limitations of manual calibration and pretesting (see [1] for a survey and [2-4] to get an idea of the papers targeting this task).
The goal of this project is to develop a model capable of performing question difficulty estimation from test in an unsupervised manner, leveraging the textual information of questions and the taxonomy of “skills” that are assessed by them.

## Datasets:
* AI2 Reasoning Challenge (ARC) 2018 ([link](https://allenai.org/data/arc))
* NeurIPS 2020 Education Challenge ([link](https://competitions.codalab.org/competitions/25449))
* A private industrial dataset might be available for this task, in case of promising results on the public dataset.

## References:
- [[1](https://dl.acm.org/doi/10.1145/3556538)] A survey on recent approaches to question difficulty estimation from text, ACM Computing Surveys
- [[2](https://dl.acm.org/doi/abs/10.1145/3375462.3375517)] R2DE: a NLP approach to estimating IRT parameters of newly generated questions, LAK20
- [[3](https://aclanthology.org/2021.ranlp-1.97/)] Towards the Application of Calibrated Transformers to the Unsupervised Estimation of Question Difficulty from Text, RANLP21
- [[4](https://aclanthology.org/2022.acl-short.15/)] Predicting Difficulty and Discrimination of Natural Language Questions, ACL22

