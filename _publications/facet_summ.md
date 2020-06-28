---
title: "Exploiting pivot words to classify and summarize discourse facets of scientific papers"
collection: publications
permalink: /publication/facet_summ
excerpt: ' This paper proposes a new, more effective solution to the CL-SciSumm discourse facet classification task, which entails identifying for each cited text span what facet of the paper it belongs to from a predefined set of facets.'
date: 2020-06-14
venue: 'Scientometrics (2020)'
paperurl: 'https://doi.org/10.1007/s11192-020-03532-3'
citation: 'La Quatra, M., Cagliero, L. & Baralis, E. Exploiting pivot words to classify and summarize discourse facets of scientific papers. Scientometrics (2020). https://doi.org/10.1007/s11192-020-03532-3'
---
The ever-increasing number of published scientific articles has prompted the need for automated, data-driven approaches to summarizing the content of scientific articles. The Computational Linguistics Scientific Document Summarization Shared Task (CL-SciSumm 2019) has recently fostered the study and development of new text mining and machine learning solutions to the summarization problem customized to the academic domain. In CL-SciSumm, a Reference Paper (RP) is associated with a set of Citing Papers (CPs), all containing citations to the RP. In each CP, the text spans (i.e., citances) have been identified that pertain to a particular citation to the RP. The task of identifying the spans of text in the RP that most accurately reflect the citance is addressed using supervised approaches. This paper proposes a new, more effective solution to the CL-SciSumm discourse facet classification task, which entails identifying for each cited text span what facet of the paper it belongs to from a predefined set of facets. It proposes also to extend the set of traditional CL-SciSumm tasks with a new one, namely the discourse facet summarization task. The idea behind is to extract facet-specific descriptions of each RP consisting of a fixed-length collection of RP’s text spans. To tackle both the standard and the new tasks, we propose machine learning supported solutions based on the extraction of a selection of discriminating words, called pivot words. Predictive features based on pivot words are shown to be of great importance to rate the pertinence and relevance of a text span to a given facet. The newly proposed facet classification method performs significantly better than the best performing CL-SciSumm 2019 participant (i.e., the classification accuracy has increased by + 8%), whereas regression methods achieved promising results for the newly proposed summarization task.

[Download paper here](https://doi.org/10.1007/s11192-020-03532-3)
[GitHub Repository](https://github.com/MorenoLaQuatra/Auto-Scientific-Annotation)

Recommended citation: La Quatra, M., Cagliero, L. & Baralis, E. Exploiting pivot words to classify and summarize discourse facets of scientific papers. Scientometrics (2020). https://doi.org/10.1007/s11192-020-03532-3
