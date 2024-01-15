---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


# About me and recent work

I'm a senior research scientist at ServiceNow Research, working on both fundamental and applied research on ML and NLP. A brief summary of recent research work is given by the following projects:

- **Defining explainable model classes**. We introduce models where internal states are matched to class-dependent patterns, so that they can be verified at testing time. Doing so yields classifiers with rejecting capabilities, and improved adversarial robustness. Results appeared in ICLR 2023.

- **Multi-lingual text-to-code search without parallel data**. In this work, we attempt to overcome limitations to code retrieval quality posed by the lack of large scale parallel data containing pairs of code snippets and natural language queries in languages other than English. We correspondingly test the following hypothesis: if a model can map from English to different types of code, and from other natural languages to English, then it can directly map from those non-English languages into of code. To do so, we introduce two new datasets. For training models, we build a corpus corresponding to paired English/Code data and combine it with existing translation datasets given by pairs of English and other natural languages. For evaluation, we make a new benchmark available containing pairs of text and code, for multiple natural and programming language pairs, namely: Spanish, Portuguese, German, and French, each paired with code snippets for: Python, Java, and JavaScript.

I've also worked alongside students in projects such as the following:

- **Post-hoc adjustment of classifiers outputs for improving robustness against spurious features**. We proposed bias unsupervised approaches to mitigate the effect of spurious features present in the training data. We apply a train-twice scheme where we first pre-train under standard empirical risk minimization, and leverage the resulting biased model to estimate and correct for latent biasing factors. Results, showing improvements upon recent baselines and bias-supervised models, were presented at NeurIPS 2023.

- **Defining general image kernel**. We explored high-dimensional permutation two-sample tests based on the maximum mean discrepancy, and found that the similarity functions defined on top of models trained with contrastive learning lead to high test power on different types of distribution shifts. For instance, our *unsupervised* approach is able to discriminate data sources with much higher probability and using less samples than previous supervised methods. We further extended the approach and built anomaly detection methods shown able to detect both adversarial attackers and out-of-distribution data on challenging benchmarks under very subtle perturbations, using only 3 to 20 samples. Results from this project were presented at NeurIPS 2023.

Finally, I've been also spending time on more applied work. In particular, I've been leading initiatives for training large language models of code.
