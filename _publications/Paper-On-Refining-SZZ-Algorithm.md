---
title: "On Refining the SZZ Algorithm with Bug Discussion Data"
collection: publications
permalink: /publications/Paper-On-Refining-SZZ-Algorithm
venue: "Empirical Software Engineering (EMSE)"
date: 2024-04-04
---

[Paper](https://poojaruhal.github.io/files/Paper-On-Refining-SZZ-Algorithm.pdf),
[Data](https://zenodo.org/records/11484723)

## ABSTRACT
### Context
Abstract Researchers testing hypotheses related to factors leading to low-quality software often rely on historical data, specifically on details regarding when defects were introduced into a codebase of interest. The prevailing techniques to determine the introduction of defects revolve around variants of the SZZ algorithm. This algorithm leverages information on the lines modified during a bug-fixing commit and finds when these lines were last modified, thereby identifying bug-introducing commits.
Problem: Despite several improvements and variants, SZZ struggles with accuracy, especially in cases of unrelated modifications or that touch files not involved in the introduction of the bug in the version control systems (aka tangled commit and ghost commits).

### Goal  
Our research investigates whether and how incorporating content retrieved from bug discussions can address these issues by identifying the related and external files and thus improve the efficacy of the SZZ algorithm.

### Method
To conduct our investigation, we take advantage of the links manually inserted by Mozilla developers in bug reports to signal which commits inserted bugs. Thus, we prepared the dataset, RoTEB, comprised of 12,472 bug reports. We first manually inspect a sample of 369 bug reports related to these bug-fixing or bug-introducing commits and investigate whether the files mentioned in these reports could be useful for SZZ. After we found evidence that the mentioned files are relevant, we augment SZZ with this information, using different strategies, and evaluate the resulting approach against multiple SZZ variations.


### Results
We define a taxonomy outlining the rationale behind developers’ references to diverse files in their discussions. We observe that bug discussions often mention files relevant to enhancing the SZZ algorithm’s efficacy. Then, we verify that integrating these file references augments the precision of SZZ in pinpointing bug-introducing commits. Yet, it does not markedly influence recall. These results deepen our comprehension of the usefulness of bug discussions for SZZ. Future work can leverage our dataset and explore other techniques to further address the problem of tangled commits and ghost commits.