---
title: "Documentation practices of developers in Polyglot environments"
collection: teaching
type: "BSc thesis"
permalink: /teaching/project-documentation-practices-developers-polyglot-environments
venue: "University of Bern, Switzerland"
date: 2023-02-01
location: "Zurich, Switzerland"
---

[Presenation](https://poojaruhal.github.io/files/Slides-documentation-practices-developers-Polyglot-environments.pdf)

### ABSTRACT
Developers write various types of information in code comments such as a summary of the class, or a description of its methods and variables in comments. These information types help developers in understanding and modifying the code. However, developers follow different comment conventions to write various information in comments. In our previous work, we found instances of developers borrowing or carrying the style from other languages. for instance, we found developers writing instance variable or usage details in Java class comments where Java style guidelines do not suggest. Similarly, in Python and Smalltalk, we found developers writing Javadoc-style comments.

Such practices create a consistency problem (consistency of comments with style guideline conventions or project conventions). Current linters or recommendation projects address consistency problems without understanding the origin of practices. In this project, we want to understand to what extent such practices are prevalent. How can we recommend developer-specific practices?

### Research questions: 
- To what extent such practices are prevalent. How can we recommend developer-specific practices?

### STEPS: 
- Take popular, heterogeneous, big open source projects.
- Identify three primary languages (Java, Python, C++)
- Identify the primary developers of these languages.
- Collect code comments of these developers in other languages.
- Identify the influence of one programming language on other languages’ projects.
- Compare their other languages project to the language style guidelines and see which kinds of commenting violations they often generate.
- Learn common patterns of violated/adherence commenting practices of developers.
- Develop a linter tailored to the background of a developer to handle such violations.
- Evaluate the linter in the real setting.


Find the first [presenation](https://poojaruhal.github.io/files/Slides-Msc-Investigating-Energy-Related-Practices.pdf) here. <br>