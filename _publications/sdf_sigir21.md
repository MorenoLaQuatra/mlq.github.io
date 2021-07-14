---
title: "Summarize Dates First: A Paradigm Shift in Timeline Summarization"
collection: publications
permalink: /publication/sdf_sigir21
excerpt: 'Timeline summarization aims at presenting long news stories in a compact manner. This paper proposes a new approach, namely Summarize Date First, which focuses on first generating date-level summaries then selecting the most relevant dates on top of summarized knowledge. In the latter stage, it performs date aggregations to consider high-level temporal references as well.'
date: 2021-07-13
venue: 'ACM SIGIR 2021'
paperurl: 'https://doi.org/10.1145/3404835.3462954'
citation: 'Moreno La Quatra, Luca Cagliero, Elena Baralis, Alberto Messina, and Maurizio Montagnuolo. 2021. Summarize Dates First: A Paradigm Shift in Timeline Summarization. In Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 21). Association for Computing Machinery, New York, NY, USA, 418–427. DOI:https://doi.org/10.1145/3404835.3462954'
---
Timeline summarization aims at presenting long news stories in a compact manner. State-of-the-art approaches first select the most relevant dates from the original event timeline then produce per-date news summaries. Date selection is driven by either per-date news content or date-level references. When coping with complex event data, characterized by inherent news flow redundancy, this pipeline may encounter relevant issues in both date selection and summarization due to a limited use of news content in date selection and no use of high-level temporal references (e.g., the past month). This paper proposes a paradigm shift in timeline summarization aimed at overcoming the above issues. It presents a new approach, namely Summarize Date First, which focuses on first generating date-level summaries then selecting the most relevant dates on top of summarized knowledge. In the latter stage, it performs date aggregations to consider high-level temporal references as well. The proposed pipeline also supports frequent incremental timeline updates more efficiently than previous approaches. We tested our unsupervised approach both on existing benchmark datasets and on a newly proposed benchmark dataset describing the COVID-19 news timeline. The achieved results were superior to state-of-the-art unsupervised methods and competitive against supervised ones.

[Download paper here](https://doi.org/10.1145/3404835.3462954)

[Repository](https://github.com/MorenoLaQuatra/SDF-TLS)

Recommended citation: Moreno La Quatra, Luca Cagliero, Elena Baralis, Alberto Messina, and Maurizio Montagnuolo. 2021. Summarize Dates First: A Paradigm Shift in Timeline Summarization. In Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR '21). Association for Computing Machinery, New York, NY, USA, 418–427. DOI:https://doi.org/10.1145/3404835.3462954
