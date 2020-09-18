---
abstract: Both electronic health records and personal health records are typically
  organized by data type, with medical problems, medications, procedures, and laboratory
  results chronologically sorted in separate areas of the chart. As a result, it can
  be difficult to find all of the relevant information for answering a clinical question
  about a given medical problem. A promising alternative is to instead organize by
  problems, with related medications, procedures, and other pertinent information
  all grouped together. A recent effort by Buchanan (2017) manually defined, through
  expert consensus, 11 medical problems and the relevant labs and medications for
  each. We show how to use machine learning on electronic health records to instead
  automatically construct these problem-based groupings of relevant medications, procedures,
  and laboratory tests. We formulate the learning task as one of knowledge base completion,
  and annotate a dataset that expands the set of problems from 11 to 32. We develop
  a model architecture that exploits both pre-trained concept embeddings and usage
  data relating the concepts contained in a longitudinal dataset from a large health
  system. We evaluate our algorithms’ ability to suggest relevant medications, procedures,
  and lab tests, and find that the approach provides feasible suggestions even for
  problems that are hidden during training. The dataset, along with code to reproduce
  our results, is available at https://github.com/asappresearch/kbc-pomr.
booktitle: Proceedings of the 5th Machine Learning for Healthcare Conference
title: Knowledge Base Completion for Constructing Problem-Oriented Medical Records
volume: '126'
year: '2020'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mullenbach20a
month: 0
tex_title: Knowledge Base Completion for Constructing Problem-Oriented Medical Records
firstpage: 198
lastpage: 222
page: 198-222
order: 198
cycles: false
bibtex_author: Mullenbach, James and Swartz, Jordan and McKelvey, T. Greg and Dai,
  Hui and Sontag, David
author:
- given: James
  family: Mullenbach
- given: Jordan
  family: Swartz
- given: T. Greg
  family: McKelvey
- given: Hui
  family: Dai
- given: David
  family: Sontag
date: 2020-09-18
address: 
container-title: Proceedings of the 5th Machine Learning for Healthcare Conference
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 9
  - 18
pdf: http://proceedings.mlr.press/v126/mullenbach20a/mullenbach20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
