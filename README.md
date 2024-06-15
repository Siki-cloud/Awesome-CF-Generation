# Awesome CF Generation
This repository contains the frontier research on counterfactual generation which is a hot topic recently.  A counterfactual is obtained by making minimal or loose changes to existing data to flip their label for a particular NLP task. The counterfactually augmented data (CAD) consists of original data and counterfactuals, also called contrast sets (Gardner et al., 2020; Atanasova et al., 2022).

Here are some examples of counterfactuals based on sentiment analysis and natural language inference tasks.

 <img src="image/cfs_example.png" width = "70%" alt="Examples of counterfactals for sentiment analysis (top) and natural language model (bottom) respectively" align=center />

## Overview
The following papers are collected and categorized according to our survey paper—— A Survey on Natural Language Counterfactual Generation. 

**Counterfactual Generation Taxonomy:**

- [Manual Generation](#manual-generation)
  
- [Gradient-based Optimization](#gradient-based-optimization)

- [Identify and then Generate](#identify-and-then-generate)
  
- [LLMs as Counterfactual Generation](#llms-as-counterfactual-generation)
  
### Reference
Matt Gardner, et al. Evaluating Models’ Local Decision Boundaries via Contrast Sets. In Findings of the Association for Computational Linguistics: EMNLP 2020, pages 1307–1323, Online. Association for Computational Linguistics.

Pepa Atanasova, et al. Fact Checking with Insufficient Evidence. Transactions of the Association for Computational Linguistics (TACL), 2022.

## Manual Generation

[Counterfactual story reasoning and generation](https://aclanthology.org/D19-1509.pdf),  EMNLP-IJCNLP 2019 

[Learning the difference that makes a difference with counterfactually-augmented data](https://openreview.net/pdf?id=Sklgs0NFvr),  ICLR 2020

[More bang for your buck: Natural perturbation for robust question answering](https://aclanthology.org/2020.emnlp-main.12.pdf), EMNLP 2020 

[Evaluating Models’ Local Decision Boundaries via Contrast Sets](https://aclanthology.org/2020.findings-emnlp.117.pdf), EMNLP finding 2020

[Automated Fact-Checking of Claims from Wikipedia](https://aclanthology.org/2020.lrec-1.849.pdf), LREC 2020

[“Call me sexist, but...”: Revisiting Sexism Detection Using Psychological Scales and Adversarial Samples](https://ojs.aaai.org/index.php/ICWSM/article/view/18085/17888), AAAI 2021

## Gradient-based Optimization

[Generate Your Counterfactuals: Towards Controlled Counterfactual Generation for Text](https://cdn.aaai.org/ojs/17594/17594-13-21088-1-2-20210518.pdf),  AAAI 2021

[Generating Realistic Natural Language Counterfactuals](https://aclanthology.org/2021.findings-emnlp.306.pdf),  EMNLP finding 2021

[A causal lens for controllable text generation](https://proceedings.neurips.cc/paper/2021/file/d0f5edad9ac19abed9e235c0fe0aa59f-Paper.pdf), NeurIPS 2021

[Counterfactual Explanation Based on Gradual Construction for Deep Networks](https://www.sciencedirect.com/science/article/pii/S0031320322004381), Pattern Recognition 2022

[Counterfactual Sentence Generation with Plug-and-Play Perturbation](https://ieeexplore.ieee.org/document/10136170), SaTML 2023

[Counterfactual generation with identifiability guarantees](https://proceedings.neurips.cc/paper_files/paper/2023/file/afda6bf3fb086eabbaf161ba1cec5a9a-Paper-Conference.pdf), NeurIPS 2023

## Identify and then Generate

[Explaining Data-Driven Document Classifications](https://www.semanticscholar.org/paper/Explaining-Data-Driven-Document-Classifications-Martens-Provost/add9930a368c1f281a1428d09ba65751edf06555), MIS Quarterly 2014


## LLMs as Counterfactual Generation

[LEWIS: Levenshtein editing for unsupervised text style transfer](https://arxiv.org/pdf/2105.08206) ACL 2021

[Unsupervised Text Style Transfer with Padded Masked Language Models](https://aclanthology.org/2020.emnlp-main.699.pdf) EMNLP 2020

[Politeness transfer: A tag and generate approach](https://aclanthology.org/2020.acl-main.169.pdf), ACL 2020

[Delete, Retrieve, Generate: A Simple Approach to Sentiment and Style Transfer](https://arxiv.org/pdf/1804.06437), NAACL 2018

[Robustness to Spurious Correlations in Text Classification via Automatically Generated Counterfactuals](https://arxiv.org/pdf/2012.10040) AAAI 2021

[Exploring the Efficacy of Automatically Generated Counterfactuals for Sentiment Analysis](https://aclanthology.org/2021.acl-long.26.pdf), ACL | IJCNLP 2021

[Beyond Accuracy: Behavioral Testing of NLP Models with CheckList](https://aclanthology.org/2020.acl-main.442.pdf) 2020 ACL

[Paws: Paraphrase adversaries from word scrambling](https://arxiv.org/pdf/1904.01130), NAACL 2019

[Linguistically-informed transformations (LIT): A method for automatically generating contrast sets](https://arxiv.org/pdf/2010.08580) ACL 2020

[Polyjuice: Generating Counterfactuals for Explaining, Evaluating, and Improving Models](https://aclanthology.org/2021.acl-long.523.pdf), ACL 2021

[Tailor: Generating and Perturbing Text with Semantic Controls](https://arxiv.org/pdf/2107.07150), ACL 2022

[A general search-based framework for generating textual counterfactual explanations](https://arxiv.org/pdf/2211.00369v2), AAAI 2024

[Generating Plausible Counterfactual Explanations for Deep Transformers in Financial Text Classification](https://arxiv.org/pdf/2010.12512), Coling (CCFB) 2020



[Counterfactual Explanation Algorithms for Behavioral and Textual Data](https://arxiv.org/pdf/1912.01819), ADAC (CCF None) 2019





[Explaining NLP Models via Minimal Contrastive Editing (MiCE)](https://aclanthology.org/2021.findings-acl.336.pdf), ACL finding 2021

[Let the CAT out of the bag: Contrastive Attributed explanations for Text](https://aclanthology.org/2022.emnlp-main.484.pdf). EMNLP 2022

[Relevance-based Infilling for Natural Language Counterfactuals](https://dl.acm.org/doi/10.1145/3583780.3615029) CKLM 2023

[Kace-Generating Knowledge-Aware Contrastive Explanations for Natural Language Inference](https://aclanthology.org/2021.acl-long.196.pdf),  ACL 2021

[CREST: A Joint Framework for Rationalization and Counterfactual Text Generation](https://arxiv.org/pdf/2305.17075), ACL 2023

[NeuroCounterfactuals: Beyond Minimal-Edit Counterfactuals for Richer Data Augmentation](https://aclanthology.org/2022.findings-emnlp.371.pdf),  EMNLP finding 2022



[AutoCAD: Automatically Generate Counterfactuals for Mitigating Shortcut Learning](https://aclanthology.org/2022.findings-emnlp.170.pdf) EMNLP finding 2022

[Controlling Text Edition by Changing Answers of Specific Questions](https://aclanthology.org/2021.findings-acl.110.pdf), ACL-IJCNLP finding 2021

[Retrieval-guided Counterfactual Generation for QA](https://aclanthology.org/2022.acl-long.117.pdf), ACL 2022

[Break, Perturb, Build: Automatic Perturbation of Reasoning Paths Through Question Decomposition](https://aclanthology.org/2022.tacl-1.7.pdf), TACL 2022

[Entity-based knowledge conflicts in question answering](https://aclanthology.org/2021.emnlp-main.565.pdf), EMNLP 2021

[EXPLAIN, EDIT, GENERATE: Rationale-sensitive counterfactual data augmentation for multi-hop fact verification](https://aclanthology.org/2023.emnlp-main.826.pdf), EMNLP 2023





[Improving Classifier Robustness through Active Generation of Pairwise Counterfactuals](https://arxiv.org/pdf/2305.13535.pdf), EMNLP finding 2023

[Llms as counterfactual explanation modules: Can chatgpt explain black-box text classifiers?](https://arxiv.org/pdf/2309.13340v1.pdf), AAAI 2024(update url, Todo) 

[DISCO: Distilling Counterfactuals with Large Language Models](https://aclanthology.org/2023.acl-long.302.pdf),  ACL 2023 

[Faithful Explanations of Black-box NLP Models Using LLM-generated Counterfactuals](https://arxiv.org/pdf/2310.00603v2.pdf), ICLR 2024

[CATfOOD: Counterfactual Augmented Training for Improving Out-of-Domain Performance and Calibration](https://aclanthology.org/2024.eacl-long.113.pdf), EACL 2024

[Explore Spurious Correlations at the Concept Level in Language Models for Text Classification](https://arxiv.org/pdf/2311.08648.pdf) arxive 2023 ( Undo in overleaf: Detect the spurious correlation between concept and label, and simply propose to use cfs to alleviate spurious.)

[A Novel Counterfactual Data Augmentation Method for Aspect-Based Sentiment Analysis](https://arxiv.org/pdf/2306.11260.pdf), ACML 2023

[CORE: A Retrieve-then-Edit Framework for Counterfactual Data Generation](https://arxiv.org/pdf/2210.04873.pdf), EMNLP finding 2022

## Other Related Papers
[Logic-guided data augmentation and regularization for consistent question answering](https://aclanthology.org/2020.acl-main.499.pdf), ACL 2020.

[People Make Better Edits: Measuring the Efficacy of LLM-Generated Counterfactually Augmented Data for Harmful Language Detection](https://aclanthology.org/2023.emnlp-main.649.pdf), EMNLP 2023 
