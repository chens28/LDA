# Comparison of LDA Learning Algorithms

This repository contains the code and documentation for an empirical comparison of two popular LDA learning algorithms: Variational Inference (Gensim Implementation) and Gibbs Sampling (Mallet Implementation). This project aims to evaluate and compare the performance of these algorithms across various text datasets.

## Project Overview

The project consists of several key stages:

- **Preprocessing:** Text datasets are preprocessed (tokenization, stopwords removal, lemmatization, and bi-grams/tri-grams creation) before modeling.
- **Training and Tuning:** We explore different configurations of the number of topics and soruce dataset for comparison between the 2 learnign algorithms. For tuning, we optimizaed for cohehernce score.
  - Train LDA model using Variational Inference with Gensim.
  - Train LDA model using Gibbs Sampling with Mallet.
- **Evaluation:** The performance of the algorithms is evaluated using the intrusion test, leveraging Large Language Models (LLM) to assess topic quality.
