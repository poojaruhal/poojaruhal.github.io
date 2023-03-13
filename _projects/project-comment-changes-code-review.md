---
title: "Comment-related changes in Code Review"
collection: projects
type: "MSc topic"
permalink: /projects/project-comment-changes-code-review
venue: "University of Zurich"
date: 2023-02-01
location: "Zurich, Switzerland"
---

## Context: 
Code review is a crucial practice for software quality assurance.
It has been widely adopted in both open-source and commercial software projects.
One of the benefits of code review is to enforce coding standards for the code.
Similar to GitHub, Gerrit is another tool that facilitates code review in which reviewers suggest changes to the author of a piece of code.
Wen et al. constructed a taxonomy of code changes that trigger changes in comments. They confirmed that 20% of changes in the code trigger comment changes. Our previous study showed that only 50% of the changes in the class comments are related to code changes. The remaining comment changes are about clarifying details of the class, formatting, and adding information. In this study, we aim to analyze such indirect changed and direct changes (in one commit).


## Problem:
Specifically, what aspects of code comments or software documentation are captured in the code review phase by reviewers is unexplored.

## Potential RQs
- What type of comment-related issues are pointed out in the code review phase? Are those issues pointed out to match coding standards?
- How often do developers fix comment-related issues? (Whether those issues are fixed by developers to match coding standards, to address a bug, or to improve the documentation)
- Do files containing frequent comment changes contain fewer bugs?


## Steps:
- Extract the commit changes of selected projects from Gerrit.
- Identify the commit that includes comment-related changes.
- Analyze reviewer comments to find the types of issues pointed out,
- Analyze the changes the authors apply to address reviewer comments.
<br>