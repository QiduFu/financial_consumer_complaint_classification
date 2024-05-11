# Financial Consumer Complaint Classification

By Qidu Fu, Yuqi Liu, Shixin Pan, Haotian Shen

## Overview
This project aims to analyze and classify consumer complaints related to financial services. Our goal is to improve complaint handling by leveraging insights from the analysis, thus helping financial institutions understand and address common issues faced by consumers.

## Dataset
The dataset used is the Consumer Complaint Database from the Consumer Financial Protection Bureau (CFPB). It includes complaints about financial products and services sent to companies for response, covering the period from March 1, 2023, to March 30, 2024, with a total of 469,799 complaints.

## Features
### Data Preprocessing
Implemented various text preprocessing techniques including:
- Removal of duplicates, NANs, and empty rows.
- Text normalization (lowercasing, removing punctuation, special characters).
- Lemmatization and stemming using NLTK.
- Feature engineering through mathematical transformations and PCA.

### Modeling
Explored several machine learning algorithms for both unsupervised and supervised learning:
- **K-Means Clustering** to identify distinct groups based on the issues.
- **Naive Bayes**, **Support Vector Machine**, and **Random Forests** for classification based on complaint narratives.
- **Gradient Boosting** and **BERT** for improved predictive performance.



