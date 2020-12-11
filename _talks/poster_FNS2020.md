---
title: "Poster presentation @ FNS 2020"
collection: talks
type: "FNS@COLING2020"
permalink: /talks/poster_fns2020
venue: "FNS @ COLING 2020"
date: 2020-12-12
location: "Barcelona, Spain (Virtual)"
---

The summarization architecture proposed for the FNS 2020 shared task is based on a three-phases process.
- Preprocessing step: clean input financial reports and annotate its content at sentence level.
- Training step: deep learning models are fine-tuned for the regression task exploiting the annotations obtained during the preprocessing step.
- Evaluation phase: is applied at document level. The sentences of each annual reports make a forward pass through the fine-tuned model to obtain the estimated relevance score.
The final summary merges sentences according to the relevance score predicted by the fine-tuned architecture.

Paper:
<br>
La Quatra, M., & Cagliero, L. (2020, December). End-to-end Training For Financial Report Summarization. In Proceedings of the 1st Joint Workshop on Financial Narrative Processing and MultiLing Financial Summarisation (pp. 118-123). [https://www.aclweb.org/anthology/2020.fnp-1.20/](https://www.aclweb.org/anthology/2020.fnp-1.20/)


<hr>
<img src='/images/poster_landscape_FNS2020.png'>


