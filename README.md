### **This is work in progress**

# GLUES: General Language Understanding Evaluation in Spanish

The GLUES Benchmark aims to collect different sources of tasks for evaluating Spanish Language Models in a unified fashion in order to develop and allow the growth of the Spanish NLP Community.


# Table of Contents
1. [Tasks](#tasks)
2. [Statistics](#statistics)
3. [Baselines](#baselines)
4. [Optional](#optional)
5. [References](#references)

# Tasks
WIP, missing task/dataset description

## Template:
* dataset
* metric(s)

## Natural Language Inference
* XNLI [1]
* accuracy


## Paraphrasing
* PAWS-X [2]
* accuracy

## Named Entity Recognition
* CoNLL 2002 task [3]
* f1 of total predicted entities

## Part-of-Speech Tagging
* UDv1.4 [4], following tthe work from [5]
* accuracy


## Dependency Parsing
* UDv2.2 [6], since it was the version for the CoNLL 2017 Shared Task [7]
* [UAS, LAS](https://linguistics.stackexchange.com/a/6895)

## Document Classification (comments ??)
* MLDoc [8]
* accuracy


# Statistics
WIP, some kind of table showing statistics about the datasets


# Baselines
WIP, current state of the art (??)


# Optional
This might not interest everyone but it has a special place in our hearts

## Document Classification
💕💕💕
* ArgumentMining2017 (multiple tasks) [9]
* top-5 accuracy, macro-averaged precision, recall and f1 (multiple tasks)


# References

[1][XNLI: Evaluating Cross-lingual Sentence Representations](https://arxiv.org/abs/1809.05053)
[2][PAWS-X: A Cross-lingual Adversarial Dataset for Paraphrase Identification](https://arxiv.org/abs/1908.11828)
[3][Introduction to the CoNLL-2002 Shared Task: Language-Independent Named Entity Recognition](https://www.aclweb.org/anthology/W02-2024/ )
[4][Universal Dependencies v1.4](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1827)
[5][Cross-Lingual Transfer Learning for POS Tagging without Cross-Lingual Resources](https://www.aclweb.org/anthology/D17-1302/)
[6][Universal Dependencies v1.4](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2837)
[7][CoNLL 2017 Shared Task](http://universaldependencies.org/conll17/)
[8][MLDoc: A Corpus for Multilingual Document Classification in Eight Languages](https://github.com/facebookresearch/MLDoc)
[9][200K+ Crowdsourced Political Arguments for a New Chilean Constitution](https://www.aclweb.org/anthology/W17-5101/)
