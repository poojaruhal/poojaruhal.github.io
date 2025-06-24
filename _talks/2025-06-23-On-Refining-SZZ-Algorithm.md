---
title: "On Refining the SZZ Algorithm with Bug Discussion Data"
collection: talks
type: "Presentation"
permalink: /talks/2025-06-23-On-Refining-SZZ-Algorithm
venue: "International Conference on Foundational Software Engineering, 2025"
date: 2025-06-23
location: "Trondheim, Norway"
---

[Slides](https://poojaruhal.github.io/files/Slides-On-Refining-SZZ-Algorithim.pdf),
[Online Slides](https://www.slideshare.net/slideshow/on-refining-szz-algorithm-bug-discussion-data-pdf/280962616),
[Paper](https://poojaruhal.github.io/files/Paper-On-Refining-SZZ-Algorithm.pdf),
[Replication Package](https://zenodo.org/records/11484723)

Abstract Researchers testing hypotheses related to factors leading to low-quality software often rely on historical data, specifically on details regarding when defects were introduced into a codebase of interest. The prevailing techniques to determine the introduction of defects revolve around variants of the SZZ algorithm. This algorithm leverages information on the lines modified during a bug-fixing commit and finds when these lines were last modified, thereby identifying bug-introducing commits.
Problem: Despite several improvements and variants, SZZ struggles with accuracy, especially in cases of unrelated modifications or that touch files not involved in the introduction of the bug in the version control systems (aka tangled commit and ghost commits). We define a taxonomy outlining the rationale behind developers’ references to diverse files in their discussions. We observe that bug discussions often mention files relevant to enhancing the SZZ algorithm’s efficacy. Then, we verify that integrating these file references augments the precision of SZZ in pinpointing bug-introducing commits. Yet, it does not markedly influence recall. These results deepen our comprehension of the usefulness of bug discussions for SZZ. Future work can leverage our dataset and explore other techniques to further address the problem of tangled commits and ghost commits.