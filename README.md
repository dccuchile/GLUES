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
* XNLI [\[1\]][1]
* accuracy

**XNLI** 

The Cross-Lingual NLI Corpus [\[1\]][1] is a evaluation dataset that extends the MNLI [\[2\]][2] dataset by adding dev and test set for 15 languages. Given a premise sentence and a hypothesis sentences, the task is to predict whether the premise entails the hypothesis (entailment), contradicts the hypothesis (contradiction), or neither (neutral). 

In this setup we train using the Spanish portion of the MNLI dataset, and use the dev and test set from the XNLI corpus. This task is evaluated by simple accuracy.



## Paraphrasing
* PAWS-X [\[2\]][2]
* accuracy

**PAWS-X**

The PAWS-X[\[3\]][3] is the multilingual version of the PAWS dataset [\[4\]][4]. The task consists in determining if two sentences are semantically equivalent or not.

The dataset provides standard (translate) train, dev and test set. It is evaluated using simple accuracy.


## Named Entity Recognition
* CoNLL 2002 task [\[3\]][3]
* f1 of total predicted entities

## Part-of-Speech Tagging
* UDv1.4 [\[4\]][4], following tthe work from [\[5\]][5]
* accuracy


## Dependency Parsing
* UDv2.2 [\[6\]][6], since it was the version for the CoNLL 2017 Shared Task [\[7\]][7]
* [UAS, LAS](https://linguistics.stackexchange.com/a/6895)

## Document Classification (comments ??)
* MLDoc [\[8\]][8]
* accuracy


# Statistics
WIP, some kind of table showing statistics about the datasets


# Baselines
WIP, current state of the art (??)


# Optional
This might not interest everyone but it has a special place in our hearts

## Document Classification
💕💕💕
* ArgumentMining2017 (multiple tasks) [\[9\]][9]
* top-5 accuracy, macro-averaged precision, recall and f1 (multiple tasks)


# References

1. [XNLI: Evaluating Cross-lingual Sentence Representations][1]
2. [A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference][2]
3. [PAWS-X: A Cross-lingual Adversarial Dataset for Paraphrase Identification][3]
4. [PAWS: Paraphrase Adversaries from Word Scrambling][4]
3. [Introduction to the CoNLL-2002 Shared Task: Language-Independent Named Entity Recognition][3]
4. [Universal Dependencies v1.4][4]
5. [Cross-Lingual Transfer Learning for POS Tagging without Cross-Lingual Resources][5]
6. [Universal Dependencies v2.2][6]
7. [CoNLL 2017 Shared Task][7]
8. [MLDoc: A Corpus for Multilingual Document Classification in Eight Languages][8]
9. [200K+ Crowdsourced Political Arguments for a New Chilean Constitution][9]

[1]: https://arxiv.org/abs/1809.05053
[2]: https://www.nyu.edu/projects/bowman/multinli/paper.pdf

[3]: https://arxiv.org/abs/1908.11828
[4]: https://arxiv.org/abs/1904.01130
[3]: https://www.aclweb.org/anthology/W02-2024/
[4]: https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1827
[5]: https://www.aclweb.org/anthology/D17-1302/
[6]: https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2837
[7]: http://universaldependencies.org/conll17/
[8]: https://github.com/facebookresearch/MLDoc
[9]: https://www.aclweb.org/anthology/W17-5101/