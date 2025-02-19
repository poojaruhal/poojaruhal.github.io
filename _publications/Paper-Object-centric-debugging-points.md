---
title: "Empirically Evaluating the Impact of Object-Centric Breakpoints  on the Debugging of Object-Oriented Programs"
collection: publications
permalink: /publications/Paper-Object-centric-debugging-points
venue: "Foundations of Software Engineering (FSE)"
date: 2025-06-17
---

[Paper](https://hal.science/hal-04948470)
[Data](https://doi.org/10.5281/zenodo.14802898),

## ABSTRACT
Debugging consists in understanding the behavior of a program to identify and correct its defects. Breakpoints are the most commonly used debugging tool and aim to facilitate the debugging process by allowing developers to interrupt a program’s execution at a source code location of their choice and inspect the state of the program.
Researchers suggest that in systems developed using object-oriented programming (OOP), traditional breakpoints may be a not effective method for debugging.
As an answer to this challenge, researchers proposed object-centric debugging, an
approach based on debugging tools that focus on objects rather than classes. However, no research has yet verified its actual impact.
To investigate the impact of object-centric breakpoints on the debugging process, we devised and conducted a controlled experiment with 81 developers who spent an average of 1 hour and 30 minutes each on the study.
The experiment required participants to complete two debugging tasks using debugging tools with vs. without  object-centric breakpoints. We found no significant effect from the use of object-centric breakpoints on the
number of actions required to debug or the effectiveness in understanding or fixing the bug. However, for one  of the two tasks, we measured a statistically significant reduction in debugging time for participants who used
object-centric breakpoints, while for the other task, there was a statistically significant increase. Our analysis suggests that the impact of object-centric breakpoints varies depending on the context and the specific nature
of the bug being addressed.