---
layout: post
title:  "Contextual Word Embedding Analysis"
info: "What linguistic properties are encoded in contextual word embeddings?"
tech: "conceptual framework, design studies, applications, evaluation studies"
demos: [{name: "Conceptual Framework", link: "https://embedding-framework.lingvis.io", img: "assets/img/framework.png", descr: "What to consider when designing applications for word embedding explanation tasks?"},
        {name: "Adapter Comparison", link: "https://adapters.demo.lingvis.io", img: "assets/img/adapters.png", descr: "Which language models encode semantic concepts such as stereotypes or word sentiment?"},
        {name: "Linguistic Properties", link: "https://lmfingerprints.lingvis.io", img: "assets/img/lmfingerprints.png", descr: "Which linguistic properties are encoded in embedding vectors in different model's layers?"},
        {name: "Impact of Function Words", link: "https://function-words.lingvis.io", img: "assets/img/function-words.png", descr: "Do models 'understand' the linguistic functionality of function words?"},
        {name: "Generated Text Comparison", link: "https://prompt-comparison.lingvis.io", img: "assets/img/prompt-comparison.png", descr: "How to effectively compare texts generated by two language models?"},
        {name: "Token Self-Similarity", link: "https://embeddings-explained.lingvis.io", img: "assets/img/interlinked-projections.png", descr: "What are the reasons for strong embedding contextualization?"}]
papers: [{pdf: "https://ieeexplore.ieee.org/abstract/document/10357717", text: "Rita Sevastjanova, Simon Vogelbacher, Andreas Spitz, Daniel Keim, and Mennatallah El-Assady. 2023. Visual Comparison of Text Sequences Generated by Large Language Models. In 2023 IEEE Visualization in Data Science (VDS), IEEE, 11-20."},
  {pdf: "https://bib.dbvis.de/publications/view/1028", text: "Rita Sevastjanova and Mennatallah El-Assady. 2023. WEC-Explainer: A Descriptive Framework. Exploring Research Opportunities for Natural Language, Text, and Data Visualization (NLVIZ) Workshop at IEEE VIS."},
  {pdf: "https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14541", text: "Rita Sevastjanova, A Kalouli, Christin Beck, Hanna Hauptmann, and Mennatallah El-Assady. 2022. LMFingerprints: Visual explanations of language model embedding spaces through layerwise contextualization scores. In Computer Graphics Forum, 295-307."},
  {pdf: "https://ieeexplore.ieee.org/abstract/document/9904461", text: "Rita Sevastjanova, Eren Cakmak, Shauli Ravfogel, Ryan Cotterell, and Mennatallah El-Assady. 2022. Visual comparison of language model adaptation. IEEE Transactions on Visualization and Computer Graphics 29, 1 (2022), 1178-1188."},
  {pdf: "https://aclanthology.org/2022.coling-1.272/", text: "* Aikaterini-Lida Kalouli, Rita Sevastjanova, Christin Beck, and Maribel Romero. 2022. Negation, coordination, and quantifiers in contextualized language models. International Conference On Computational Linguistics (COLING); (2022)."},
  {pdf: "https://bib.dbvis.de/publications/view/993", text: "Rita Sevastjanova and Mennatallah El-Assady. 2022. Beware the Rationalization Trap! When Language Model Explainability diverges from our Mental Models of Language. Communication in Human-AI Interaction Workshop at IJCAI-ECAI'22; (2022)."},
  {pdf: "https://aclanthology.org/2021.acl-long.39/", text: "Rita Sevastjanova, Aikaterini-Lida Kalouli, Christin Beck, Hanna Schäfer, and Mennatallah El-Assady. 2021. Explaining Contextualization in Language Models using Visual Analytics. In Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), Association for Computational Linguistics, 464-476."}
]
---

I am working on different projects related to contextual word embedding analysis. Understanding embedding potentials and limitations can help to make decisions, e.g., when to use embeddings for text analysis tasks and, more specific, which model's and layer's embeddings to use for a particular task at hand.