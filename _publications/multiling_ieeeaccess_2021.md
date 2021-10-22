---
title: "Inferring Multilingual Domain-Specific Word Embeddings From Large Document Corpora"
collection: publications
permalink: /publication/multiling_embedding_inference
excerpt: ' This paper proposes a new methodology to automatically infer aligned domain-specific word embeddings for a target language on the basis of the general-purpose and domain-specific models available for a source language (typically, English). The proposed inference method relies on a two-step process, which first automatically identifies domain-specific words and then opportunistically reuses the non-linear space transformations applied to the word vectors of the source language.'
date: 2021-10-05
venue: 'IEEE Access (2021)'
paperurl: 'https://doi.org/10.1109/ACCESS.2021.3118093'
citation: 'L. Cagliero and M. La Quatra, "Inferring Multilingual Domain-Specific Word Embeddings From Large Document Corpora," in IEEE Access, vol. 9, pp. 137309-137321, 2021, doi: 10.1109/ACCESS.2021.3118093.'
---
The use of distributed vector representations of words in Natural Language Processing has become established. To tailor general-purpose vector spaces to the context under analysis, several domain adaptation techniques have been proposed. They all require sufficiently large document corpora tailored to the target domains. However, in several cross-lingual NLP domains both large enough domain-specific document corpora and pre-trained domain-specific word vectors are hard to find for languages other than English. This paper aims at tackling the aforesaid issue. It proposes a new methodology to automatically infer aligned domain-specific word embeddings for a target language on the basis of the general-purpose and domain-specific models available for a source language (typically, English). The proposed inference method relies on a two-step process, which first automatically identifies domain-specific words and then opportunistically reuses the non-linear space transformations applied to the word vectors of the source language in order to learn how to tailor the vector space of the target language to the domain of interest. The performance of the proposed method was validated via extrinsic evaluation by addressing the established word retrieval task. To this aim, a new benchmark multilingual dataset, derived from Wikipedia, has been released. The results confirmed the effectiveness and usability of the proposed approach.

[Download paper here](https://doi.org/10.1109/ACCESS.2021.3118093)
[GitHub Repository](https://github.com/MorenoLaQuatra/AMED)

Recommended citation: L. Cagliero and M. La Quatra, "Inferring Multilingual Domain-Specific Word Embeddings From Large Document Corpora," in IEEE Access, vol. 9, pp. 137309-137321, 2021, doi: 10.1109/ACCESS.2021.3118093.
