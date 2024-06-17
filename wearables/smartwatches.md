---
layout: default
title: Smartwatches and Rings
nav_order: 2
parent: Wearables
grand_parent: MassAITC Resources
has_children: false
usemathjax: true
description: "Smartwatch Wearables"
---
## Smartwatch and Smartring Wearables
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

# Measuring Cardiac Health with Wearable Smartwatches and SmartRings

Wearable smartwatches have become increasingly popular due to their accessibility, ease of use, and the rich array of sensors they contain, which have improved significantly over multiple product generations. These devices offer great promise for remote monitoring, particularly for older adults, by providing continuous data that can help detect early signs of cognitive decline, physical deterioration, and behavioral changes. However, deploying these technologies in studies focused on older populations involves navigating several challenges. Issues such as device bias, usability, data accuracy, and the physical burden of wearing the devices need careful consideration. While extensive research on the efficacy of wearables in younger cohorts exists, there is a relative scarcity of studies specifically addressing their use among older adults or those with Alzheimer's Disease and Related Dementias (AD/ADRD). This section explores the potential challenges and evaluates the validity of data derived from wearables, aiding researchers in understanding their limitations and capabilities before integrating them into pilot projects.

## Challenges and Opportunities when using Wearables in Pilot Studies

<iframe width="560" height="315" src="https://www.youtube.com/embed/mTdeiz4KFe4?si=oGrvX5qQvPWkOITw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

In the above talk at the mHealth Training Institute, MassAITC Co-Director Dr. Deepak Ganesan's discusses the challenges and considerations involved in deploying wearable sensing systems for clinical problems, using the example of detecting early symptoms of COVID-19. He emphasized the importance of collaboration between clinicians and engineers to determine the most appropriate sensors and metrics for the study, taking into account factors such as the desired physiological parameters, sensor modalities, and trade-offs between comfort, accuracy, and capabilities of different devices.

Dr. Ganesan highlighted the importance of understanding the limitations and inaccuracies of wearable monitors, which can vary based on factors such as skin tone, physical activity, and pre-existing health conditions. He stressed the need for a deeper understanding of these issues beyond what is provided by device manufacturers, as well as the rapid evolution of devices and algorithms that can complicate comparisons across studies.

The talk also covered the signal analysis pipeline for wearable sensor data, including windowing, noise removal, feature extraction, and classification. Dr. Ganesan emphasized the importance of incorporating domain knowledge into feature selection and the need for high-quality data, noting that large amounts of poor-quality data cannot be easily compensated for by machine learning techniques.

Finally, Dr. Ganesan discussed the trade-offs between classical machine learning models and deep learning approaches, highlighting the need for large amounts of labeled data for deep learning and the importance of interpretability in some clinical contexts. He concluded by emphasizing the importance of a holistic understanding of the interrelated factors involved in wearable sensing studies and the critical role of data quality in achieving meaningful results.

## Validation of Heart Rate and Heart Rate Variability from wearables

Heart rate (HR) and heart rate variability (HRV) are important indicators of cardiovascular health and autonomic function, which can be affected in older adults and those with Alzheimer's disease (AD), Alzheimer's disease-related dementias (ADRD), or other forms of dementia. 

Miller et al  [[1]](#1) examined the validity of six wearable devices (Apple Watch S6, Garmin Forerunner 245 Music, Polar Vantage V, Oura Ring Generation 2, WHOOP 3.0, and Somfit) for assessing HR and HRV compared to electrocardiography (ECG). For HR measurement, the devices demonstrated moderate to almost perfect relative agreement with ECG. Apple Watch, Polar, Oura Gen 2, and WHOOP 3.0 had excellent intraclass correlations (>0.85), while Garmin and Somfit had fair to good intraclass correlations (0.41 and 0.65, respectively). For HRV measurement, the devices that sampled during sleep (Apple Watch, Oura Gen 2, WHOOP 3.0, and Somfit) had moderate to high relative agreement with ECG. WHOOP 3.0, which provided raw R-R interval data, demonstrated the highest agreement for both HR and HRV. The findings suggest that the better-performing devices can provide valid measures of HR and HRV in the absence of gold-standard ECG, which could be valuable for monitoring cardiovascular health and autonomic function in older adults and those with cognitive impairments.

## Validation of SpO2 measurements from wearable smartwatches

Blood oxygen saturation (SpO2) monitoring is crucial for older adults, particularly those with Alzheimer's disease, Alzheimer's disease-related dementias (ADRD), or other forms of dementia. These individuals are at a higher risk of developing respiratory conditions, such as pneumonia, which can lead to low blood oxygen levels. Additionally, they may have pre-existing chronic conditions, such as chronic obstructive pulmonary disease (COPD) or heart failure, which can also affect blood oxygen levels. Continuous, non-invasive monitoring of SpO2 using smartwatches could help detect deterioration early and promote timely interventions, ultimately improving patient safety and outcomes.

In the study by Jiang et al. [[2]](#2), four consumer smartwatches (Apple Watch Series 7, Garmin Venu 2s, Garmin Fenix 6 Pro, and Withings ScanWatch) were compared against a clinical-grade pulse oximeter (Masimo MightySat Rx) in patients aged 18-85 years old, with and without respiratory disease. The Apple Watch Series 7 demonstrated the highest accuracy, with 58.3% of readings falling within the accuracy range of the reference device and the lowest mean absolute error (MAE) of 2.2%. The Garmin Venu 2s had the highest percentage of underestimated readings (67.4%) and the highest MAE of 5.8%. The Withings ScanWatch and Garmin Fenix 6 Pro had the highest data missingness at 31% and 28%, respectively, indicating poor reliability in obtaining measurements.

The implications of these findings suggest that while smartwatches have the potential to provide continuous, non-invasive SpO2 monitoring for older adults and those with AD/ADRD/dementia, their accuracy and reliability vary significantly across devices. The Apple Watch Series 7 appears to be the most accurate and reliable option among the devices tested. However, further research is needed to validate these findings in larger, more diverse populations and to explore the potential impact of skin tone on measurement accuracy. As smartwatch technology continues to advance, it is crucial to ensure that these devices are rigorously validated and meet the specific needs of older adults and those with cognitive impairments to support their use in remote monitoring and early detection of respiratory deterioration.

<a id="1">[1]</a> 
Miller, Dean J., Charli Sargent, and Gregory D. Roach. "A validation of six wearable devices for estimating sleep, heart rate and heart rate variability in healthy adults." Sensors 22, no. 16 (2022): 6317.

<a id="2">[2]</a> 
[1] Y Jiang, C Spies, J Magin, SJ Bhosai, L Snyder, and J Dunn. Investigating the accuracy of blood oxygen saturation measurements in common consumer smartwatches. PLOS digital health 2, no. 7 (2023).

