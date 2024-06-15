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

[Delete, Retrieve, Generate: A Simple Approach to Sentiment and Style Transfer](https://aclanthology.org/N18-1169.pdf), NAACL 2018

[Mask and Infill: Applying Masked Language Model for Sentiment Transfer](https://www.ijcai.org/proceedings/2019/0732.pdf), IJCAI 2019

[PAWS: Paraphrase Adversaries from Word Scrambling](https://aclanthology.org/N19-1131.pdf), NAACL-HLT 2019

[Politeness transfer: A tag and generate approach](https://aclanthology.org/2020.acl-main.169.pdf), ACL 2020

[Unsupervised Text Style Transfer with Padded Masked Language Models](https://aclanthology.org/2020.emnlp-main.699.pdf), EMNLP 2020

[Linguistically-informed transformations (LIT): A method for automatically generating contrast sets](https://aclanthology.org/2020.blackboxnlp-1.12.pdf) ACL 2020

[Beyond Accuracy: Behavioral Testing of NLP Models with CheckList](https://aclanthology.org/2020.acl-main.442.pdf) 2020 ACL

[Generating Plausible Counterfactual Explanations for Deep Transformers in Financial Text Classification](https://aclanthology.org/2020.coling-main.541.pdf), Coling (CCFB) 2020

[A comparison of instance-level counterfactual explanation algorithms for behavioral and textual data: SEDC, LIME-C and SHAP-C](https://dl.acm.org/doi/10.1007/s11634-020-00418-3), ADAC 2020

[Logic-guided data augmentation and regularization for consistent question answering](https://aclanthology.org/2020.acl-main.499.pdf), ACL 2020.

[LEWIS: Levenshtein editing for unsupervised text style transfer](https://aclanthology.org/2021.findings-acl.344.pdf), ACL 2021

[Polyjuice: Generating Counterfactuals for Explaining, Evaluating, and Improving Models](https://aclanthology.org/2021.acl-long.523.pdf), ACL 2021

[Explaining NLP Models via Minimal Contrastive Editing (MiCE)](https://aclanthology.org/2021.findings-acl.336.pdf), ACL finding 2021

[Robustness to Spurious Correlations in Text Classification via Automatically Generated Counterfactuals](https://cdn.aaai.org/ojs/17651/17651-13-21145-1-2-20210518.pdf) AAAI 2021

[CrossAug: A Contrastive Data Augmentation Method for Debiasing Fact Verification Models](https://dl.acm.org/doi/abs/10.1145/3459637.3482078), CIKM 2021

[Exploring the Efficacy of Automatically Generated Counterfactuals for Sentiment Analysis](https://aclanthology.org/2021.acl-long.26.pdf), ACL | IJCNLP 2021

[Entity-based knowledge conflicts in question answering](https://aclanthology.org/2021.emnlp-main.565.pdf), EMNLP 2021

[Controlling Text Edition by Changing Answers of Specific Questions](https://aclanthology.org/2021.findings-acl.110.pdf), ACL-IJCNLP finding 2021

[KACE: Generating Knowledge Aware Contrastive Explanations for Natural Language Inference](https://aclanthology.org/2021.acl-long.196.pdf),  ACL 2021

[Reinforced Counterfactual Data Augmentation for Dual Sentiment Classification](https://aclanthology.org/2021.emnlp-main.24.pdf), EMNLP 2021

[Learning Models for Actionable Recourse](https://proceedings.neurips.cc/paper/2021/file/9b82909c30456ac902e14526e63081d4-Paper.pdf), NeurIPS 2021

[Text Counterfactuals via Latent Optimization and Shapley-Guided Search](https://aclanthology.org/2021.emnlp-main.452.pdf), EMNLP 2021

[Sketch and Customize: A Counterfactual Story Generator](https://ojs.aaai.org/index.php/AAAI/article/view/17532/17339), AAAI 2021

[Tailor: Generating and Perturbing Text with Semantic Controls](https://aclanthology.org/2022.acl-long.228.pdf), ACL 2022

[Retrieval-guided Counterfactual Generation for QA](https://aclanthology.org/2022.acl-long.117.pdf), ACL 2022

[Break, Perturb, Build: Automatic Perturbation of Reasoning Paths Through Question Decomposition](https://aclanthology.org/2022.tacl-1.7.pdf), TACL 2022

[AutoCAD: Automatically Generate Counterfactuals for Mitigating Shortcut Learning](https://aclanthology.org/2022.findings-emnlp.170.pdf), EMNLP finding 2022

[Let the CAT out of the bag: Contrastive Attributed explanations for Text](https://aclanthology.org/2022.emnlp-main.484.pdf), EMNLP 2022

[NeuroCounterfactuals: Beyond Minimal-Edit Counterfactuals for Richer Data Augmentation](https://aclanthology.org/2022.findings-emnlp.371.pdf),  EMNLP finding 2022

[DoCoGen: Domain Counterfactual Generation for Low Resource Domain Adaptation](https://aclanthology.org/2022.acl-long.533.pdf), ACL 2022

[Unsupervised Editing for Counterfactual Stories](https://ojs.aaai.org/index.php/AAAI/article/view/21290/21039), AAAI 2022

[EXPLAIN, EDIT, GENERATE: Rationale-sensitive counterfactual data augmentation for multi-hop fact verification](https://aclanthology.org/2023.emnlp-main.826.pdf), EMNLP 2023

[Relevance-based Infilling for Natural Language Counterfactuals](https://dl.acm.org/doi/10.1145/3583780.3615029) CKLM 2023

[CREST: A Joint Framework for Rationalization and Counterfactual Text Generation](https://aclanthology.org/2023.acl-long.842.pdf), ACL 2023

[Towards Model Robustness: Generating Contextual Counterfactuals for Entities in Relation Extraction](https://dl.acm.org/doi/abs/10.1145/3543507.3583504), WWW 2023

[SCENE: Self-Labeled Counterfactuals for Extrapolating to Negative Examples](https://aclanthology.org/2023.emnlp-main.485.pdf), EMNLP 2023

[Generating Commonsense Counterfactuals for Stable Relation Extraction](https://aclanthology.org/2023.emnlp-main.344.pdf), EMNLP 2023

[CLICK: Integrating Causal Inference and Commonsense Knowledge Incorporation for Counterfactual Story Generation](https://www.mdpi.com/2079-9292/12/19/4173), Electronics 2023

[A general search-based framework for generating textual counterfactual explanations](https://ojs.aaai.org/index.php/AAAI/article/view/29764/31316), AAAI 2024

[A Novel Counterfactual Data Augmentation Method for Aspect-Based Sentiment Analysis](https://proceedings.mlr.press/v222/wu24a/wu24a.pdf), ACML 2023

[Counterfactual-Enhanced Information Bottleneck for Aspect-Based Sentiment Analysis](https://ojs.aaai.org/index.php/AAAI/article/view/29726/31247), AAAI 2024

## LLMs as Counterfactual Generation

[CORE: A Retrieve-then-Edit Framework for Counterfactual Data Generation](https://aclanthology.org/2022.findings-emnlp.216.pdf), EMNLP finding 2022

[DISCO: Distilling Counterfactuals with Large Language Models](https://aclanthology.org/2023.acl-long.302.pdf),  ACL 2023 

[CATfOOD: Counterfactual Augmented Training for Improving Out-of-Domain Performance and Calibration](https://aclanthology.org/2024.eacl-long.113.pdf), EACL 2024

[Faithful Explanations of Black-box NLP Models Using LLM-generated Counterfactuals](https://openreview.net/pdf?id=UMfcdRIotC), ICLR Poster 2024

[LLMs for Generating and Evaluating Counterfactuals: A Comprehensive Study](https://arxiv.org/pdf/2405.00722), arXiv preprint 2024

[Prompting Large Language Models for Counterfactual Generation: An Empirical Study](https://aclanthology.org/2024.lrec-main.1156.pdf), LREC-COLING 2024

[Towards LLM-guided Causal Explainability for Black-box Text Classifiers](https://arxiv.org/pdf/2309.13340), AAAI Workshop 2024


## Other Related Papers

[People Make Better Edits: Measuring the Efficacy of LLM-Generated Counterfactually Augmented Data for Harmful Language Detection](https://aclanthology.org/2023.emnlp-main.649.pdf), EMNLP 2023 

[Improving Classifier Robustness through Active Generation of Pairwise Counterfactuals](https://aclanthology.org/2023.findings-emnlp.10.pdf), EMNLP finding 2023

[Explore Spurious Correlations at the Concept Level in Language Models for Text Classification](https://arxiv.org/pdf/2311.08648.pdf), arXive Preprint 2023 
