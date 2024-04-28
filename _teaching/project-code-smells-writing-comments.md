---
title: "Impact of code smells on writing code comments"
collection: teaching
type: "Seminar"
permalink: /teaching/project-code-smells-writing-comments
venue: "University of Zurich, Switzerland"
date: 2024-03-01
location: "Zurich, Switzerland"
---


### ABSTRACT
Code comments play a crucial role in program comprehension and maintenance. 
On the one hand, studies show that developers trust code comments and find useful information in them.  
Begel and Zimmermann conducted a survey to understand the challenges in their development practices and highlighted the question, “When are code comments worth the effort to write them?” [2]. There are various factors that make developers add comments to their code [1]. For example, the complexity of a file might cause developers to add comments to it, or if a code has various code smells, developers might want to add comments to better explain their code.
Code smells indicate the complexity of code and various design issues that code can have. 

## Aim
We aim to find the impact of various code smells that can play a role in writing comments.

## Steps: 
- Identify the smells that can play a role in the tendency of writing or not writing comments. The smells can be identified by conducting a brief literature review.
- Mine open-source projects from GitHub.
- Extract various metrics from them, such as developers' experience, profile, programming language, and comments. 
Identify a statistical model (e.g., correlation model) to model the factors.
- Find the impact of various factors on adding comments. 
 Compute the statistical significance of various factors and highlight the important ones. 

## References
- [1] D. P. Marin. What motivates programmers to comment. Technical Report No. UCB/EECS-2005018, University of California at Berkeley, 2005
- [2] Begel, Andrew, and Thomas Zimmermann. "Analyze this! 145 questions for data scientists in software engineering." Proceedings of the 36th International Conference on Software Engineering. 2014.

