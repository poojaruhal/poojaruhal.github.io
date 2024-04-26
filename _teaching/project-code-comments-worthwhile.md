---
title: "Factors behind writing code comments"
collection: teaching
type: "MSc"
permalink: /teaching/project-code-comments-worthwhile
venue: "University of Zurich, Switzerland"
date: 2024-03-01
location: "Zurich, Switzerland"
---


### ABSTRACT
Code comments play a crucial role in program comprehension and maintenance. 
On the one hand, studies show that developers trust code comments and find useful information in them. 
On the other hand, developers find comments outdated, misleading, and often inconsistent with code.  Thus, they often question whether it is worth adding comments or not.  
Begel and Zimmermann conducted a survey to understand the challenges in their development practices and highlighted the question, “When are code comments worth the effort to write them?” [2]. There are various factors that make developers add comments to their code [1]. For example, the complexity of a file might cause developers to add comments to it, or experienced developers can favor adding comments more than novice ones? 

## Aim
We aim to find similar factors that can play a role in comment writing [1]. 

When developers find code comments worth the effort to write them?

## Steps: 
- Identify the factors that can play a role in the tendency of writing or not writing comments. The factors can be identified by conducting a brief literature review.
- Mine open-source projects from GitHub. (we already have a dataset for Java and Python developers from https://bitbucket.org/swsc/overview/src/master/).
- Extract various metrics from them, such as developers' experience, profile, programming language, and comments. 
Identify a statistical model (e.g., logistic regression) to model the factors.
- Find the impact of various factors on adding comments. 
 Compute the statistical significance of various factors and highlight the important ones. 

## References
- [1] D. P. Marin. What motivates programmers to comment. Technical Report No. UCB/EECS-2005018, University of California at Berkeley, 2005
- [2] Begel, Andrew, and Thomas Zimmermann. "Analyze this! 145 questions for data scientists in software engineering." Proceedings of the 36th International Conference on Software Engineering. 2014.

