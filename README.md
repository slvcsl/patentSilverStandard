# Creating a Silver Standard for Patent Simplification
This repo contains the materials for the paper "Creating a Silver Standard for Patent Simplification" (SIGIR 2023).

This repo is WIP. 
If you have any questions, feel free to contact me. 


Please cite:
```
@inproceedings{10.1145/3539618.3591657,
author = {Casola, Silvia and Lavelli, Alberto and Saggion, Horacio},
title = {Creating a Silver Standard for Patent Simplification},
year = {2023},
isbn = {9781450394086},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3539618.3591657},
doi = {10.1145/3539618.3591657},
abstract = {Patents are legal documents that aim at protecting inventions on the one hand and at making technical knowledge circulate on the other. Their complex style -- a mix of legal, technical, and extremely vague language -- makes their content hard to access for humans and machines and poses substantial challenges to the information retrieval community. This paper proposes an approach to automatically simplify patent text through rephrasing. Since no in-domain parallel simplification data exist, we propose a method to automatically generate a large-scale silver standard for patent sentences. To obtain candidates, we use a general-domain paraphrasing system; however, the process is error-prone and difficult to control. Thus, we pair it with proper filters and construct a cleaner corpus that can successfully be used to train a simplification system. Human evaluation of the synthetic silver corpus shows that it is considered grammatical, adequate, and contains simple sentences.},
booktitle = {Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval},
pages = {1045–1055},
numpages = {11},
keywords = {patents, text simplification, natural language processing},
location = {Taipei, Taiwan},
series = {SIGIR '23}
}
```