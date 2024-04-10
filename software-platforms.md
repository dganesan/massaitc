---
layout: default
title: Software Infrastructure
nav_order: 1
parent: MassAITC Resources
has_children: true
usemathjax: true
description: "Software Infrastructure"
---
## Software Infrastructure for Pilot Studies
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## Software Platforms for Remote Pilot Studies involving Sensors, EMAs, and Digital Recruitment 

The importance of having a software infrastructure that is capable of managing remote clinical trials cannot be overstated. These platforms facilitate a variety of critical functions including participant recruitment, integration with wearables, smartphones and Internet of Things (IoT) devices, the deployment of Ecological Momentary Assessments (EMAs) and digital surveys such as RedCAP, and running different types of assessments. Effective software solutions can greatly simplify the time and effort to roll out a remote pilot study.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xdmH4UaOBUA?si=uNgYSEZW9wVgOC0V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

There are a number of tradeoffs when selecting a platform to run your mHealth study. As Dr. Predjag Klasnja says in his webinar (see above), there are various options to consider including commercial software and hardware, white label solutions, hybrid systems, and custom systems. Each approach has its advantages and disadvantages in terms of usability, functionality, cost, and technical requirements. Commercial software and hardware are polished and well-maintained but may lack specific features needed for research. White label solutions offer more customization and responsive technical support but can be expensive and may not fit all project requirements. Hybrid systems combine commercial components with custom code, allowing researchers to focus on novel features while leveraging existing functionality, but integration can be suboptimal. Custom systems provide the most control over the user experience and data collection but are complex, time-consuming, and prone to bugs. 

Ultimately, the speaker emphasizes that there is no perfect solution, and researchers should strive to find the best compromise based on their specific needs and resources. Regardless of the chosen approach, mobile health studies are becoming increasingly complex and sophisticated, requiring extensive testing and collaboration with experts in different fields. Researchers should expect trade-offs and be prepared to handle bugs and unexpected issues.

Below, we describe two available platforms, one commercial from CareEvolution which supports many remote studies including the {All of Us} study [https://careevolution.com/case-studies/facilitating-precision-medicine-research-through-the-all-of-us-research-program/], and one research grade from a large consortium performing AD-specific mHealth studies.

### Care Evolution

CareEvolution MyDataHelps is a platform for remote trials. The platform allows users to build surveys, schedule real-time notifications, launch projects, and digitally recruit participants without need to program. Participants join projects via the MyDataHelps app (available on iOS, Android, and web) to provide real-world participant health data from wearables, devices with EHR data, and EMAs. MyDataHelps integrates with a variety of wearable platforms including Apple Watch, Fitbit, Garmin, and others, as well as survey platforms such as RedCAP. They offer a free  account which allows you to invite and enroll up to 100 participants in your project. 

See Dr. Edward Ramos's MassAITC seminar on *Opportunities for Clinical Research Using a Digital, Decentralized Study Approach.*
<iframe width="320" height="240" src="https://www.youtube.com/embed/FXBL5xMj9ig?si=p6blVDPtcrKPLoVk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Radar-AD

RADAR-base is an open-source platform used for horizontally-scalable remote data collection. The main function of RADAR-base is to provide modular tools for the integration of data streams from various sources (i.e. wearables, phones, apps, IoT etc) and to collect in real time, process, store, manage and share the data with researchers. 

Ranjan, Yatharth, Zulqarnain Rashid, Callum Stewart, Pauline Conde, Mark Begale, Denny Verbeeck, Sebastian Boettcher, Richard Dobson, Amos Folarin, and RADAR-CNS Consortium. "RADAR-base: open source mobile health platform for collecting, monitoring, and analyzing data using sensors, wearables, and mobile devices." JMIR mHealth and uHealth 7, no. 8 (2019): e11734.


