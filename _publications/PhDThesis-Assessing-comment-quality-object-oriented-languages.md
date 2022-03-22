---
title: "Assessing Comment Quality in Object-Oriented Languages"
collection: publications
permalink: /publications/PhDThesis-Assessing-comment-quality-object-oriented-languages
venue: "PhD defense, 2022"
date: 2022-01-31
location: "University of Bern, Switzerland"
citation: ' <b>Pooja Rani</b>'
---

[Thesis](https://poojaruhal.github.io/files/PhDThesis-pooja-rani.pdf), 
[University](https://boristheses.unibe.ch/3382/)
[Presenation](https://poojaruhal.github.io/files/Slides-Assessing-comment-quality-in-object-oriented-languages.pdf),

## ABSTRACT
Previous studies have shown that high-quality code comments support developers in software maintenance and program comprehension tasks. However, the semi-structured nature of comments, several conventions to write comments, and the lack of quality assessment tools for all aspects of comments make comment evaluation and maintenance a non-trivial problem. To understand the specification of high-quality comments to build effective assessment tools, our thesis emphasizes acquiring a multi-perspective view of the comments, which can be approached by analyzing (1) the academic support for comment quality assessment, (2) developer commenting practices across languages, and (3) developer concerns about comments. 

Our findings regarding the academic support for assessing comment quality showed that researchers primarily focus on Java in the last decade even though the trend of using polyglot environments in software projects is increasing. Similarly, the trend of analyzing specific types of code comments (method comments, or inline comments) is increasing, but the studies rarely analyze class comments. We found 21 quality attributes that researchers consider to assess comment quality, and manual assessment is still the most commonly used technique to assess various quality attributes. Our analysis of developer commenting practices showed that developers embed a mixed level of details in class comments, ranging from high-level class overviews to low-level implementation details across programming languages. They follow style guidelines regarding what information to write in class comments but violate the structure and syntax guidelines. They primarily face problems locating relevant guidelines to write consistent and informative comments, verifying the adherence of their comments to the guidelines, and evaluating the overall state of comment quality. 

To help researchers and developers in building comment quality assessment tools, we contribute: (i) a systematic literature review (SLR) of ten years (2010–2020) of research on assessing comment quality, (ii) a taxonomy of quality attributes used to assess comment quality, (iii) an empirically validated taxonomy of class comment information types from three programming languages, (iv) a multi-programming-language approach to automatically identify the comment information types, (v) an empirically validated taxonomy of comment convention-related questions and recommendation from various Q&A forums, and (vi) a tool to gather discussions from multiple developer sources, such as Stack Overflow, and mailing lists. Our contributions provide various kinds of empirical evidence of the developer’s interest in reducing efforts in the software documentation process, of the limited support developers get in automatically assessing comment quality, and of the challenges they face in writing high-quality comments. This work lays the foundation for future effective comment quality assessment tools and techniques.