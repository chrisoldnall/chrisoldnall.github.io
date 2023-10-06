---
layout: archive
title: "Research Projects"
permalink: /researchprojects/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

So far, research projects I have been involved with have been wide ranging and included a vast range of stakeholders. Having started with my masters research dissertation in causal inference for epidemiology, I then worked in stochastic optimisation for CO2 removal. Following this I then worked in generalised linear modelling for public health, before now working on my full time PhD topic of causal effect estimation using Mendelian randomisation. Further details of each of these projects can be found below.

Current Research Projects
====

Currently I am working on the project entitled, "Identifying causal effect sizes in population genetics via targeted Mendelian randomisation." Researchers, in the field of bio-medicine, are often interested identifying which set of biological exposures are causal of trait or disease. Due to advances in the field of causal inference in recent years, both in terms of causal identifiability and estimation, the causal effect of a variable on an outcome in the presence of unobserved confounders can be estimated, under certain assumptions. A common technique in to achieve this is known as the instrumental variable (IV) approach. Here an additional variable is introduced and the exposure of interest is conditioned on this variable. In the case where the instrument Z is a DNA variant, inherited at birth and essentially unchanging over a life time, the IV approach is known as Mendelian Randomisation (MR), a common approach to infer causality in population genetics. 

Despite widespread application in the biomedical literature, certain assumptions underlying the validity of MR are often violated in practice. One such violation is the DNA variant being used affects the outcome through some other pathway than just that of the exposure. This situation is termed, pleiotropy. My project looks to apply Mendelian randomisation techniques to a range of exposure and outcome situations, as well as to develop statistically sound methodology for tackling the situation of pleiotropy - acknowleding that it is commonly accepted that one cannot easily identify which DNA variants may be pleiotropic.

Previous Research Projects
====
## January 2022 - April 2022
Understanding the public health waiting times landscape in Scotland: Finding key drivers and forecasting demand. [with M.Brunet-Gusasch and S.Verhees]

This report presents a data-driven analysis of cancer waiting times in Scotland. We analysed open data provided by Public Health Scotland with records of the numbers of patients that were referred and/or treated within 31 and 62 days in different regions. Our goal when analysing this data was twofold. First, we aimed to explore the effect of the COVID-19 pan- demic on the number of cancer referrals and diagnoses. Secondly, we aimed to identify the important factors underlying variation in cancer referrals and diagnoses, such as region or cancer type. Most of our work relied on the application of Generalised Linear Models. Overall, this report shows that the pandemic resulted in a reduction of rates of referral and diagnosis of cancer in Scotland. Moreover, our analysis suggests that these are significantly determined by region, cancer type and age. However, the open source data provided by Public Health Scotland is not sufficient to draw conclusions on the cancer waiting times in Scotland.

**[Download report here](http://chrisoldnall.github.io/files/publichealthscotland2022.pdf)
Recommended citation: Brunet-Guasch, Meritxell and Oldnall, Christopher A and Verhees, Sofie. (2022). "Understanding the Public Health Waiting Times Landscape in Scotland: Finding Key Drivers and Forecasting Demand." <i>Unpublished</i>.**

## September 2021 - December 2021
Optimal infrastructure planning for the removal of CO2 from the atmosphere. [with L.Beerens and L.Llamazares]

In this paper we explore the usage of stochastic optimization in deploying an infrastructure built of pipes and ships within the UK in order to transport CO2 from clusters (sources) to sequestration sites in parts of the Northern Sea and East Irish Sea (sinks). After visiting some background of the problem, this paper looks to implement a multistage stochastic linear framework with a nodal formulation. The implementation will lead to a model which can show the most efficient layout of the infrastructure to transport the most CO2 based on a stochastic variable of unknown CO2 capture from each cluster.

**[Download report here](http://chrisoldnall.github.io/files/optimalinfrastructure2021.pdf)
Recommended citation: Beerens, Lucas and Llamazares, Liam and Oldnall, Christopher A. (2021). "Optimal Infrastructure Planning for the Removal of CO2 from the Atmosphere." <i>Unpublished</i>.**


Masters Research Project
====
As part of my MMath award, I conducted research in to causal inference in epidemiology. This thesis looks at providing the reader with some basic causal inference theory, and then follows by applying this within the epidemiological setting.

[Download dissertation here](http://chrisoldnall.github.io/files/causalinferenceepidemiology.pdf)
Recommended citation: Oldnall, Christopher A. (2021). "Causal Inference in Epidemiology: The Effect of Socio-economic Intervention." <i>Unpublished</i>.