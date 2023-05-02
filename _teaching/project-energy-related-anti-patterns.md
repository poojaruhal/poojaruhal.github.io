---
title: "Impact of energy patterns in web applications"
collection: teaching
type: "Seminar topic"
permalink: /teaching/project-energy-related-anti-patterns
venue: "University of Zurich"
date: 2023-02-01
location: "Zurich, Switzerland"
---

## Context: 
The intensive use of software in many aspects of industries is becoming more and more common. Including other factors impacting climate, the technology sector also plays a role.
Therefore, in recent years, software engineering research has attempted to comprehend the energy consumption and implication of the software development process by building various tools and frameworks[1]. However, not all developers are aware of sustainable software, or energy-efficient practices; therefore, energy-related anti-patterns are more common than expected, and eventually, developing green software is still challenging.

## Problem:
This study aims at assessing the impact of various energy-related patterns proposed by Cruz et al.
Cruz et al. developed a catalog of 22 design patterns related to the energy efficiency of mobile apps.   Some patterns are applicable in Web development as well. We find the anti-patterns that consume more energy than others. We assess their impact on selected open-source projects[2][3]. We also design a pilot study to understand the strategies that can be adopted to avoid them.

## Steps:
-  Study the 22 energy patterns. 
- Identify the tools (e.g., Intel’s Running Average Power Limit (RAPL) interface) to measure the impact of the patterns in open-source web applications[4]. 
- Identify the patterns that consume more energy. 
- Explore the strategies that can be used to avoid the anti-patterns.

## Related work:
1. Pinto et al, Mining Questions about Software Energy Consumption, 2014, https://dl.acm.org/doi/pdf/10.1145/2597073.2597110
2. Tahir et al., A large scale study on how developers discuss code smells and anti-patterns in Stack Exchange sites, 2020, https://www.sciencedirect.com/science/article/pii/S0950584920300926
3. Procaccianti et al. 2016, “Empirical evaluation of two best practices for energy-efficient software development” https://doi.org/10.1016/j.jss.2016.02.035
4. Shanbhag et al. “Onthe Energy Consumption of Different Dataframe Processing Libraries- An Exploratory Study”, https://arxiv.org/pdf/2209.05258.pdf <br>