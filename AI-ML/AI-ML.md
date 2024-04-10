---
layout: default
title: AI & ML
nav_order: 6
parent: MassAITC Resources
has_children: true
usemathjax: true
description: "AI & ML"
---
## AI & ML
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

# Machine Learning for mHealth Pilots 

The integration of machine learning (ML) into mobile health (mHealth) pilot studies represents a significant development in the application of advanced analytics to enhance healthcare delivery. Machine learning techniques enable the analysis of large volumes of data from wearables and other sensors, providing deeper insights into patient health and facilitating the customization of healthcare interventions.

<iframe width="560" height="315" src="https://www.youtube.com/embed/OCadQgthWjc?si=Zs_9qvr6NHcOSXvZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

In this talk, Dr. Benjamin Marlin, MassAITC Associate Director, discusses the application of machine learning approaches in mobile health (mHealth) and builds a conceptual model to understand how machine learning fits into the mHealth context. The model includes observational and interventional study designs, where machine learning is used to mediate between the state and outcome information inferred about the participant or environment and the data collected via various modalities. Machine learning is also used to optimize the selection of intervention components in just-in-time adaptive interventions.

Dr. Marlin presents an overview of the machine learning toolkit, which includes methods for inference, prediction, data representation, and decision making. The main categories of machine learning problems discussed are classification, regression, clustering, dimensionality reduction, and reinforcement learning. Each category is explained with examples from various domains, highlighting their potential applications in mHealth.

He also provides a detailed walkthrough of the application of machine learning methods for state inference, specifically focusing on smoking puff detection using respiration data from a chest band sensor. The process involves featurization of the raw sensor data, labeling the data with ground truth, and learning a classification function that can predict whether a new respiration cycle corresponds to a smoking puff or a regular non-puff cycle. Dr. Marlin emphasizes the importance of considering the broader context of deploying machine learning models in mHealth, including data collection, cleaning, feature extraction, and model evaluation.

## Challenges for ML in mHealth

Implementing machine learning in mHealth presents several challenges. Dr. Marlin also highlights six key issues that need to be addressed when applying machine learning techiques to mHealth studies. We encourage pilots to consider these issues when applying machine learning techniques to their data, and reach out to your MassAITC mentor if you questions.

* **Label scarcity**: Collecting a sufficient number of accurate labels in mHealth can be difficult and costly due to trade-offs between ecological validity and fidelity of label collection.
* **Feature design**: Effective feature engineering is crucial for machine learning to work well in mHealth. Deep learning approaches can help extract good representations from data but typically require more data.
* **Incompleteness**: Input data in mHealth are rarely completely observed due to issues like non-wear and non-compliance with self-reported items, which can cause problems for most machine learning methods.
* **Lab to field generalization**: Models trained on lab data may fail to generalize well to the field due to differences in ecological validity and the context in which the data are collected.
* **Between-subject variability**: Small studies with diverse participants can make model building difficult, as there may not be enough similar individuals to learn from, leading to issues with generalization to new subjects.
* **Algorithmic bias**: Standard machine learning models can learn biases based on the composition of the input cohorts, potentially leading to systematic underperformance on underrepresented groups in the data.

## Open software packages

The use of open software packages in mHealth is crucial due to the complex nature of transforming raw data into usable digital biomarkers. Open-source platforms enable collaborative development and sharing of advancements, making sophisticated data processing tools more accessible. They also help manage the computational demands and technical complexities associated with developing and applying machine learning models, thus fostering innovation in mHealth research.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8m5llOl39z4?si=3EQi-T7veB9adbvx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

In this talk, Dr. Jessica Dunn introduces the Digital Biomarker Discovery Pipeline (DBDP), an open-source toolbox for biosignal analysis aimed at addressing challenges in mobile health (mHealth) research, such as sensor accuracy, data interoperability, and data volume. The DBDP provides a repository of code, data, and algorithms to make digital biomarker discovery more accessible and establish best practices in the field. The Digital Biomarker Discovery Project provides a number of useful tools from accessing and preprocessing sensor data to development of statistical modeling, machine learning, and deep learning algorithms.

Dr. Dunn presents two case studies to demonstrate the DBDP's capabilities in addressing sensor accuracy and validation challenges. The first case study involves validating heart rate measurements from consumer wearables against a reference standard ECG device. The study reveals that device type and physical activity affect heart rate accuracy, with no significant impact of skin tone on the devices tested. The second case study assesses and monitors a consumer wearable for circadian rhythm monitoring, highlighting gaps in existing tools and the development of patches for future studies.

To address the challenge of data deluge, Dr. Dunn discusses strategies for minimizing data volumes while maximizing the accuracy of digital biomarkers. These strategies include reducing signal-level data collection, developing application-driven data compression methods, and intelligently aggregating data. Dr. Dunn emphasizes the importance of collaboration within the mHealth community to leverage wearables and sensor data for patient empowerment, precision therapies, just-in-time interventions, and improved access to care.


