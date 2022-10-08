# Awesome Reasoning over Tables [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)

> A comprehensive paper list of awesome reasoning over tables.

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
#### 2020
* TaBERT: Learning Contextual Representations for Natural Language Utterances and Structured Tables (ACL 2020) [[Paper](https://aclanthology.org/2020.acl-main.745/)][[Github](https://github.com/facebookresearch/TaBERT)] 
* TAPAS: Weakly Supervised Table Parsing via Pre-training (ACL 2020) [[Paper](https://aclanthology.org/2020.acl-main.398/)][[Github](https://github.com/google-research/tapas)] 

#### 2021
* TABBIE: Pretrained Representations of Tabular Data (NAACL 2021) [[Paper](https://aclanthology.org/2021.naacl-main.270/)][[Github](https://github.com/SFIG611/tabbie)] 
* Capturing Row and Column Semantics in Transformer Based Question Answering over Tables (NAACL 2021) [[Paper](https://aclanthology.org/2021.naacl-main.96/)][[Github](https://github.com/IBM/row-column-intersection)] 
* GraPPa: Grammar-Augmented Pre-Training for Table Semantic Parsing (ICLR 2021) [[Paper](https://openreview.net/forum?id=kyaIeYj4zZ)][[Huggingface](https://huggingface.co/Salesforce/grappa_large_jnt)] 
* TUTA: Tree-based Transformers for Generally Structured Table Pre-training (KDD 2021) [[Paper](https://arxiv.org/abs/2010.12537)]
* MATE: Multi-view Attention for Table Transformer Efficiency (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.600/)][[Github](https://github.com/google-research/tapas)] 
* Understanding tables with intermediate pre-training (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2020.findings-emnlp.27/)][[Github](https://github.com/google-research/tapas)] 
* UnifiedSKG: Unifying and Multi-Tasking Structured Knowledge Grounding with Text-to-Text Language Models (EMNLP 2022) [[Paper](https://arxiv.org/pdf/2201.05966.pdf)][[Github](https://github.com/HKUNLP/UnifiedSKG)] 
* TAPEX: Table Pre-training via Learning a Neural SQL Executor (ICLR 2022) [[Paper](https://openreview.net/pdf?id=O50443AsCP)][[Github](https://github.com/microsoft/Table-Pretraining)] 

#### 2022
* TableFormer: Robust Transformer Modeling for Table-Text Encoding (ACL 2022) [[Paper](https://arxiv.org/pdf/2203.00274.pdf)][[Github](https://github.com/google-research/tapas/blob/master/TABLEFORMER.md)] 
* OmniTab: Pretraining with Natural and Synthetic Data for Few-shot Table-based Question Answering (NAACL) [[Paper](https://arxiv.org/pdf/2207.03637.pdf)][[Github](https://github.com/jzbjyb/OmniTab)] 


## (Faithful) Table-to-Text Generation
### Datasets/Benchmark
#### 2020
* Logical Natural Language Generation from Open-Domain Tables (ACL 2020) [[Paper](https://aclanthology.org/2020.acl-main.708/)][[Github](https://github.com/wenhuchen/LogicNLG)] 
* ToTTo: A Controlled Table-To-Text Generation Dataset (EMNLP 2020) [[Paper](https://aclanthology.org/2020.emnlp-main.89/)][[Github](https://github.com/google-research-datasets/totto)]

#### 2021
* SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables (NIPS 2021) [[Paper](https://openreview.net/forum?id=Jul-uX7EV_I)][[Github](https://github.com/UKPLab/SciGen)]
* HiTab: A Hierarchical Table Dataset for Question Answering and Natural Language Generation (Pre-print 2021) [[Paper](https://arxiv.org/abs/2108.06712)]
* TWT: Table with Written Text for Controlled Data-to-Text Generation (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.107/)][[Github](https://github.com/tonyliangli/TWT)]

### Models
#### 2021
* Towards Table-to-Text Generation with Numerical Reasoning (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.115/)]
* De-Confounded Variational Encoder-Decoder for Logical Table-to-Text Generation (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.430/)]
* Few-Shot Table-to-Text Generation with Prototype Memory (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.77/)]
* Attend, Memorize and Generate: Towards Faithful Table-to-Text Generation in Few Shots (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.77/)][[Github](https://github.com/google-research-datasets/totto)]

#### 2022
* Robust (Controlled) Table-to-Text Generation with Structure-Aware Equivariance Learning (NAACL 2022) [[Paper](https://aclanthology.org/2022.naacl-main.371.pdf)][[Github](https://github.com/luka-group/Lattice)]
* R2D2: Robust Data-to-Text with Replacement Detection (EMNLP 2022) [[Paper](https://arxiv.org/pdf/2205.12467.pdf)][[Github](https://github.com/Yale-LILY/r2d2)]
* PLOG: Table-to-Logic Pretraining for Logical Table-to-Text Generation (EMNLP 2022) [[Paper](https://arxiv.org/pdf/2205.12697.pdf)][[Github](https://github.com/Aolius/logic-pretraining)]
* Diversity Enhanced Table-to-Text Generation via Type Control (Pre-print) [[Paper](https://arxiv.org/pdf/2205.10938.pdf)]

## Reasoning over Tabular Data
### Datasets/Benchmark
#### 2020
* TabFact: A Large-scale Dataset for Table-based Fact Verification (ICLR 2020) [[Paper](https://openreview.net/forum?id=rkeJRhNYDH)][[Github](https://github.com/wenhuchen/Table-Fact-Checking)]

#### 2021
* FeTaQA: Free-form Table Question Answering (TACL 2021) [[Paper](https://arxiv.org/abs/2104.00369)][[Github](https://github.com/Yale-LILY/FeTaQA)]
* HiTab: A Hierarchical Table Dataset for Question Answering and Natural Language Generation (Pre-print 2021) [[Paper](https://arxiv.org/abs/2108.06712)]

### Models
#### 2021
* Joint Verification and Reranking for Open Fact Checking Over Tables (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.529/)][[Github](https://github.com/facebookresearch/OpenTableFactChecking)]
* Logic-level Evidence Retrieval and Graph-based Verification Network for Table-based Fact Verification (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.16/)][[Blank Github](https://github.com/qshi95/LERGV)]
* Exploring Decomposition for Table-based Fact Verification (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.90/)]
* Table-based Fact Verification With Salience-aware Learning (EMNLP-findings 2021) [[Paper](https://aclanthology.org/2021.findings-emnlp.338/)][[Github]( luka-group/salience-aware-learning)]

#### 2022
* Learning to Generate Programs for Table Fact Verification via Structure-Aware Semantic Parsing (ACL 2022) [[Paper](https://aclanthology.org/2022.acl-long.525.pdf)][[Github](https://github.com/ousuixin/SASP)]

## Reasoning over Tabular and Textual Data (Hybrid Data)
### Datasets/Benchmark
#### 2020
* HybridQA: A Dataset of Multi-Hop Question Answering over Tabular and Textual Data (EMNLP-findings 2020) [[Paper](https://aclanthology.org/2020.findings-emnlp.91/)][[Github](https://github.com/wenhuchen/HybridQA)]

#### 2021
* Open Question Answering over Tables and Text (ICLR 2021) [[Paper](https://openreview.net/forum?id=MmCRswl1UYl)][[Github](https://github.com/wenhuchen/OTT-QA)]
* MultiModalQA: complex question answering over text, tables and images (ICLR 2021) [[Paper](https://openreview.net/forum?id=ee6W5UgQLa)]
* TSQA: Tabular Scenario Based Question Answering (AAAI 2021) [[Paper](https://arxiv.org/abs/2101.11429)][[Github](https://github.com/nju-websoft/TSQA)]
* TAT-QA: A Question Answering Benchmark on a Hybrid of Tabular and Textual Content in Finance (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.254/)][[Github](https://github.com/NExTplusplus/tat-qa)]
* FinQA: A Dataset of Numerical Reasoning over Financial Data (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.300/)][[Github](https://github.com/czyssrs/FinQA)]

#### 2022
* MultiHiertt: Numerical Reasoning over Multi Hierarchical Tabular and Textual Data (ACL 2022) [[Paper](https://aclanthology.org/2022.acl-long.454.pdf)][[Github](https://github.com/psunlpgroup/MultiHiertt)]
* Learning to Imagine: Integrating Counterfactual Thinking in Neural Discrete Reasoning (ACL 2022) [[Paper](https://aclanthology.org/2022.acl-long.5.pdf)]
* HybriDialogue: An Information-Seeking Dialogue Dataset Grounded on Tabular and Textual Data (ACL-findings 2022) [[Paper](https://aclanthology.org/2022.findings-acl.41.pdf)][[Github](https://github.com/entitize/HybridDialogue)]


### Models
#### 2021
* Open Domain Question Answering over Tables via Dense Retrieval (NAACL 2021) [[Paper](https://aclanthology.org/2021.naacl-main.43/)][[Github](https://github.com/google-research/tapas)]

#### 2022
* FinMath: Injecting a Tree-structured Solver for Question Answering over Financial Reports (LREC 2022) [[Paper](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.661.pdf)]
* Towards Complex Document Understanding By Discrete Reasoning (MM 2022) [[Paper](https://arxiv.org/pdf/2209.07692.pdf)][[Github](https://nextplusplus.github.io/TAT-DQA/)]
* Answering Numerical Reasoning Questions in Table-Text Hybrid Contents with Graph-based Encoder and Tree-based Decoder (COLING 2022) [[Paper](https://arxiv.org/pdf/2207.11871.pdf)][[Github](https://github.com/lfy79001/RegHNT)]

## Other directions
### Robustness
#### 2021
* Towards Robustness of Text-to-SQL Models against Synonym Substitution (ACL 2021) [[Paper](https://aclanthology.org/2021.acl-long.195/)][[Github](https://github.com/ygan/Spider-Syn)]
* Topic Transferable Table Question Answering (EMNLP 2021) [[Paper](https://aclanthology.org/2021.emnlp-main.342/)][[Github](https://github.com/IBM/T3QA)]

#### 2022
Bridging the Generalization Gap in Text-to-SQL Parsing with Schema Expansion (ACL 2022) [[Paper](https://aclanthology.org/2022.acl-long.381.pdf)][[Github](https://github.com/microsoft/text-to-sql-schema-expansion-generalization)]

## Tutorials
#### 2021
* KDD 2021 Tutorial: From Tables to Knowledge: Recent Advances in Table Understanding [[Website](https://usc-isi-i2.github.io/KDD21Tutorial/index.html)]
* EMNLP 2021 Tutorial: Knowledge-Enriched Natural Language Generation [[Website](https://kenlg-tutorial.github.io/)]

## Contributing
Please feel free to make a pull request or email Yilun Zhao (yilun.zhao@yale.edu) for any interesting updates.
