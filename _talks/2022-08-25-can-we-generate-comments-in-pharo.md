---
title: "Can We Automatically Generate Class Comments in Pharo?"
collection: talks
type: "Presentation"
permalink: /talks/2022-08-25-can-we-generate-comments-in-pharo 
venue: "International Conference on Smalltalk Tehcnologies (IWST), 2022"
date: 2022-08-25
location: "Novi Sad, Serbia"
---

[Slides](https://poojaruhal.github.io/files/Slides-Can-we-automatically-generate-class-comments-in-Pharo.pdf)

[Online](https://www.slideshare.net/PoojaRuhal/can-we-automatically-generate-class-comments-in-pharo-252697644)

Code comments support developers in understanding and maintaining codebases. Specifically in the Pharo environment, code comments serve as the main form of code documentation and usually convey information ranging from high-level design descriptions to low-level implementation details. Nevertheless, numerous important classes in Pharo still lack comments as developers find writing comments to be a tedious and effort-intensive task. 

Previous works in Java have recommended generating comments automatically to reduce commenting effort and save developers time. There exist several approaches to achieve this goal. One such popular approach is based on identifying stereotypes, i.e., a generalized set of characteristics supposed to represent an entity (object, class). However, this approach has not been tested for other programming languages. In this paper, we adopt the stereotype-based approach to automatically generate class comments in the Pharo programming environment.