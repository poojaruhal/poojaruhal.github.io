---
title: "How do code documentation efforts spread over class hierarchy?"
collection: projects
permalink: /projects/project-how-code-documentation-efforts-spread-class-hierarchy
venue: "University of Bern, Switzerland"
date: 2022
---

[Presenation](https://poojaruhal.github.io/files/Slides-How-code-documentation-efforts-spread-class-hierarchy.pdf)

## ABSTRACT
Inheritance plays an essential role in object-oriented programming languages. It claims to aid in maintaining software, testing it, and producing high-quality software. As a class inherits another class, similarly documentation is also inherited in the subclasses. In Java, JavaDoc automatically inherits the superclass method’s comments in case there are no method comments provided for the overridden method. However, in practice, how deep the documentation hierarchy goes and how information is spread over different hierarchy levels is unknown. For example, In Pharo, 90% of root classes have longer comments than leaf classes. On the other hand, leaf classes can be documented by test cases, separate example class/methods, or examples in the comments.

### Aim: 
To gather the information on how classes are documented, by class comments, method comments, test cases, or examples and design a visualization to present to the developers.

### Research hypothesis: 
Leaf classes have more examples compared to root classes.

### Steps:
- Gather several projects in Java.
- Gather information about how classes are documented.
- Identify at which inheritance level classes are documented often.
- Design a visualization to present the class documentation hierarchy.
- Analyze the role of hierarchy in the class documentation.
