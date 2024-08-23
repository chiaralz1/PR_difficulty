# Investigating Text Difficulty and Prerequisite Relation Identification
Data and analysis of the crowd-based study on concept prerequisite ordering.

This GitHub repository contains the corpus and linguistic analysis of a crowd-based study on prerequisite concept ordering. 
In the study, we aimed to understand how people order concepts in a variety of domains after reading short concept descriptions showing various text difficulty degrees. 
This repository is intended to provide transparency, access to the collected data, and insights gained from our linguistic analysis.

# Concept Ordering Task

*Prerequisite concept ordering* is a novel task which consists of manually ordering concepts according to the ideal sequence in which they should be presented in educational materials. 

The task is formally defined as follows: 
Given three concepts A, B, and C, each described in a short text t_A, t_B and t_C, create a triple of prerequisites T = (t_A < t_B < t_C) to indicate that A is a prerequisite of B and B is a prerequisite of C. 

To test whether the produced orderings vary depending on the difficulty level of the concept description, we acquired the short texts from three different sources: Simple Wikipedia, English Wikipedia, and Specialised Encyclopaedia.

# Repository Contents
- *Corpus Data*: This directory contains the concept descriptions used for the crowd-based study. These descriptions constitute the core part of the **Concept Description Variations Corpus**. For each concept description source (Simple Wikipedia, English Wikipedia and Specialised Encyclopedia), we report the 10 triples used as questions of the study. Specifically, for each question, we report:
i) A progressive number serving as an identifier;
ii) The name of concept A, the alphanumeric code used to mask the concept name in the descriptions, and the short descriptive text (same for concepts B and C).
iii) The correct sequence in which concepts should be ordered.
  
- *Linguistic Analysis*: Here, you can find the results of the linguistic analysis performed on the collected data. The folder also contains a legend which details the linguistic features extracted from the texts.

- *Questionnaires Results*: This folder contains the aggregated answers to the questionnaires provided by participants. For each question (identified by the id) and each possible concept ordering, we report the number of subjects who gave that ordering as an answer. 


When using this resource, please cite the following paper:
Alzetta C. (2024) “Investigating Text Difficulty and Prerequisite Relation Identification”. In Italian Journal of Computational Linguistics (IJCoL), Volume 10, Number 1. https://journals.openedition.org/ijcol/1362
