# Roadmap for Reasoning over Tabular Data

An annotated bibliography of tutorials, datasets, papers for Reasoning over Tabular Data. The papers in each list are sorted according to publish time.

## Table of Contents

- [Table Representation Learning](#Table-Representation-Learning)
- [Logical Text Generation over Tabular Data](#Logical-Text-Generation-over-Tabular-Data)
- [Reasoning over Tabular Data](#Reasoning-over-Tabular-Data)
- [Reasoning over Hybrid Data](#Reasoning-over-Hybrid-Data)
- [Other directions](#Other-directions)
- [Tutorials](#Tutorials)

## Table Representation Learning
### Graph Representation
* A Graph Representation of Semi-structured Data for Web Question Answering (COLING 2020) [[Paper](https://aclanthology.org/2020.coling-main.5/)]
* Retrieving Complex Tables with Multi-Granular Graph Representation Learning (SIGIR 2021) [[Paper](https://arxiv.org/abs/2105.01736)][[Github](https://github.com/FeiWang96/GTR)] 

### Transformer-Based
* TaBERT: Learning Contextual Representations for Natural Language Utterances and Structured Tables (ACL 2020) [[Paper](https://aclanthology.org/2020.acl-main.745/)][[Github](https://github.com/facebookresearch/TaBERT)] 
* TAPAS: Weakly Supervised Table Parsing via Pre-training (ACL 2020) [[Paper](https://aclanthology.org/2020.acl-main.398/)][[Github](https://github.com/google-research/tapas)] 
* Understanding tables with intermediate pre-training (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2020.findings-emnlp.27/)][[Github](https://github.com/google-research/tapas)] 
* TABBIE: Pretrained Representations of Tabular Data (NAACL 2021) [[Paper](https://aclanthology.org/2021.naacl-main.270/)][[Github](https://github.com/SFIG611/tabbie)] 
* Capturing Row and Column Semantics in Transformer Based Question Answering over Tables (NAACL 2021) [[Paper](https://aclanthology.org/2021.naacl-main.96/)][[Github](https://github.com/IBM/row-column-intersection)] 
* GraPPa: Grammar-Augmented Pre-Training for Table Semantic Parsing (ICLR 2021) [[Paper](https://openreview.net/forum?id=kyaIeYj4zZ)][[Huggingface](https://huggingface.co/Salesforce/grappa_large_jnt)] 
* TUTA: Tree-based Transformers for Generally Structured Table Pre-training (KDD 2021) [[Paper](https://arxiv.org/abs/2010.12537)]
* MATE: Multi-view Attention for Table Transformer Efficiency (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.600/)][[Github](https://github.com/google-research/tapas)] 


## Logical Text Generation over Tabular Data
### Datasets
* Logical Natural Language Generation from Open-Domain Tables (ACL 2020) [[Paper](https://aclanthology.org/2020.acl-main.708/)][[Github](https://github.com/wenhuchen/LogicNLG)] 
* ToTTo: A Controlled Table-To-Text Generation Dataset (EMNLP 2020) [[Paper](https://aclanthology.org/2020.emnlp-main.89/)][[Github](https://github.com/google-research-datasets/totto)]
* SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables (NIPS 2021) [[Paper](https://openreview.net/forum?id=Jul-uX7EV_I)][[Github](https://github.com/UKPLab/SciGen)]
* HiTab: A Hierarchical Table Dataset for Question Answering and Natural Language Generation (Pre-print 2021) [[Paper](https://arxiv.org/abs/2108.06712)]
* TWT: Table with Written Text for Controlled Data-to-Text Generation (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.107/)][[Github](https://github.com/tonyliangli/TWT)]

### Papers
* Towards Table-to-Text Generation with Numerical Reasoning (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.115/)]
* De-Confounded Variational Encoder-Decoder for Logical Table-to-Text Generation (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.430/)]
* Few-Shot Table-to-Text Generation with Prototype Memory (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.77/)]
* Attend, Memorize and Generate: Towards Faithful Table-to-Text Generation in Few Shots (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.77/)][[Blank Github](https://github.com/google-research-datasets/totto)]


## Reasoning over Tabular Data
### Datasets
* TabFact: A Large-scale Dataset for Table-based Fact Verification (ICLR 2020) [[Paper](https://openreview.net/forum?id=rkeJRhNYDH)][[Github](https://github.com/wenhuchen/Table-Fact-Checking)]
* FeTaQA: Free-form Table Question Answering (TACL 2021) [[Paper](https://arxiv.org/abs/2104.00369)][[Github](https://github.com/Yale-LILY/FeTaQA)]
* HiTab: A Hierarchical Table Dataset for Question Answering and Natural Language Generation (Pre-print 2021) [[Paper](https://arxiv.org/abs/2108.06712)]
### Papers
* Joint Verification and Reranking for Open Fact Checking Over Tables (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.529/)][[Github](https://github.com/facebookresearch/OpenTableFactChecking)]
* Logic-level Evidence Retrieval and Graph-based Verification Network for Table-based Fact Verification (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.16/)][[Blank Github](https://github.com/qshi95/LERGV)]
* Exploring Decomposition for Table-based Fact Verification (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.90/)]
* Table-based Fact Verification With Salience-aware Learning (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.338/)][[Github]( luka-group/salience-aware-learning)]

## Reasoning over Tabular and Textual Data (Hybrid Data)
This is a very new area, and most of current works are focusing on proposing new benchmarks.
### Datasets
* HybridQA: A Dataset of Multi-Hop Question Answering over Tabular and Textual Data (EMNLP-findings 2020) [[Paper](https://aclanthology.org/2020.findings-emnlp.91/)][[Github](https://github.com/wenhuchen/HybridQA)]
* Open Question Answering over Tables and Text (ICLR 2021) [[Paper](https://openreview.net/forum?id=MmCRswl1UYl)][[Github](https://github.com/wenhuchen/OTT-QA)]
* MultiModalQA: complex question answering over text, tables and images (ICLR 2021) [[Paper](https://openreview.net/forum?id=ee6W5UgQLa)]
* TSQA: Tabular Scenario Based Question Answering (AAAI 2021) [[Paper](https://arxiv.org/abs/2101.11429)][[Github](https://github.com/nju-websoft/TSQA)]
* TAT-QA: A Question Answering Benchmark on a Hybrid of Tabular and Textual Content in Finance (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.254/)][[Github](https://github.com/NExTplusplus/tat-qa)]
* FinQA: A Dataset of Numerical Reasoning over Financial Data (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.300/)][[Github](https://github.com/czyssrs/FinQA)]

### Papers
* Open Domain Question Answering over Tables via Dense Retrieval (NAACL 2021) [[Paper](https://aclanthology.org/2021.naacl-main.43/)][[Github](https://github.com/google-research/tapas)]



## Other directions
### Robustness
* Towards Robustness of Text-to-SQL Models against Synonym Substitution (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.195/)][[Github](https://github.com/ygan/Spider-Syn)]
* Topic Transferable Table Question Answering (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.342/)][[Github](https://github.com/IBM/T3QA)]
### Efficient Training
* Turning Tables: Generating Examples from Semi-structured Tables for Endowing Language Models with Reasoning Skills (Pre-print) [[Paper](https://arxiv.org/abs/2107.07261)][[Github](https://github.com/oriyor/turning_tables)]

## Tutorials
### KDD'21 Tutorial: From Tables to Knowledge: Recent Advances in Table Understanding [[Website](https://usc-isi-i2.github.io/KDD21Tutorial/index.html)]
* Understanding Table Structures [[slides](https://usc-isi-i2.github.io/KDD21Tutorial/1-KDD2021-FT2K-Structural-Table-Understanding.pdf)] by _Jay Pujara_
* Semantic Understanding of Tables [[slides](https://usc-isi-i2.github.io/KDD21Tutorial/2-KDD2021-FT2K-Semantic-Models.pdf)] by _Pedro Szekely_
* Representation Learning for Tables [[slides](https://usc-isi-i2.github.io/KDD21Tutorial/3-KDD2021-FT2K-Representation-Learning.pdf)] by _Huan Sun_
* Bridging Tables and Language [[slides](https://usc-isi-i2.github.io/KDD21Tutorial/4-KDD2021-FT2K-human-languages.pdf)] by _Muhao Chen_

### EMNLP 2021 Tutorial: Knowledge-Enriched Natural Language Generation [[Website](https://kenlg-tutorial.github.io/)]
* General Methods of Integrating Knowledge into NLG [[slides(Hu)](https://kenlg-tutorial.github.io/tutorial/part2.pdf)][[slides(Rajani)](https://kenlg-tutorial.github.io/tutorial/part3.pdf)] by _Zhiting Hu, Nazneen Rajani_
* NLG Methods Enhanced by Various Knowledge Source [[slides](https://kenlg-tutorial.github.io/tutorial/part4.pdf)] by _Wenhao Yu_


## Contributing
Please feel free to make a pull request or email Yilun Zhao (yilun.zhao@yale.edu) for any interesting updates.
