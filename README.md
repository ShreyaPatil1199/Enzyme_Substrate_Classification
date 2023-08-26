# Enzyme-Substrate Classification Project

![image](https://github.com/ShreyaPatil1199/Enzyme_Substrate_Classification/assets/135635788/17d7048c-7804-489d-bcd3-9ea43a2a3158)

![GitHub last commit](https://img.shields.io/github/last-commit/{Shreya_Patil}/{Enzyme_Substrate_Classification})

![Python](https://img.shields.io/badge/Python-3-blue.svg) 

## Table of Contents 

- [Overview](#Overview)

- [Objective](#Objective)

- [Dataset](#Dataset)

- [Citations](#Citations)



## Overview

The Enzyme-Substrate Classification Project aims to build predictive models using various machine-learning algorithms to map the relationships between enzymes and their possible substrates. Enzymes, as catalysts, facilitate one or more specific reactions, and understanding the associations between enzymes and their potential substrates holds significant utility in various domains, including bioinformatics, drug discovery, and biotechnology.

## Objective

The primary objective of this project is to develop accurate and robust classification models using the following machine-learning algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- Ensemble Techniques
  
	 * Gradient Classifier
  
	 * Extreme Gradient Classifier

## Dataset

- train.csv: This file contains the training data and includes features related to enzyme-substrate interactions. Each row represents an observation with various feature values, along with the corresponding target labels indicating the presence or absence of specific enzyme-substrate relationships. The dataset has been generated using a deep learning model trained on a subset of the Multi-label Classification of enzyme substrates, focusing on features that demonstrated the most signal. The distribution of features in this dataset is close to, but not exactly the same as the original dataset, adding novelty and challenge to the classification task.

- test.csv: This file contains the test data, which is similar in structure to the training data but lacks the target labels. Participants are required to use their trained models to predict the enzyme-substrate relationships for the test samples.

The project is organized as follows:

- `data/`: This directory contains the dataset files (train and test).
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and evaluation ( ipynb and PDF )

## Citations

1. Bastard, K. et al. Revealing the hidden functional diversity of an enzyme family. Nature Chemical Biology 10, 42–49 (2014).

2. Black, G. W. et al. A high-throughput screening method for determining the substrate scope of nitrilases. Chemical Communications 51, 2660–2662 (2015).

3. Davis, M. I. et al. Comprehensive analysis of kinase inhibitor selectivity. Nature Biotechnology 29, 1046–1051 (2011).

4. Hie, B., Bryson, B. D. & Berger, B. Leveraging uncertainty in machine learning accelerates biological discovery and design. Cell Systems 11, 461-477. e9 (2020).

5. Huang, H. et al. Panoramic view of a superfamily of phosphatases through substrate profiling. PNAS 112, E1974–E1983 (2015).

6. Li, T. et al. Exploration of transaminase diversity for the oxidative conversion of natural amino acids into 2-ketoacids and high-value chemicals. ACS Catalysis 10, 7950–7957 (2020).

7. Martínez-Martínez, M. et al. Determinants and Prediction of Esterase Substrate Promiscuity Patterns. ACS Chem. Biol. 13, 225–234 (2018).

8. Robinson, S. L., Smith, M. D., Richman, J. E., Aukema, K. G. & Wackett, L. P. Machine learning-based prediction of activity and substrate specificity for OleA enzymes in the thiolase superfamily. Synth Biol 5, (2020).

9. Yang, M. et al. Functional and informatics analysis enables glycosyltransferase activity prediction. Nature Chemical Biology 14, 1109–1117 (2018).

