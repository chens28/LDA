# Comparison of LDA Learning Algorithms

This repository contains the code and documentation for an empirical comparison of two popular LDA learning algorithms: Variational Inference (Gensim Implementation) and Gibbs Sampling (Mallet Implementation). This project aims to evaluate and compare the performance of these algorithms across various text datasets.

## Project Overview

The project consists of several key stages:

- **Preprocessing:** Text datasets are preprocessed (tokenization, stopwords removal, lemmatization, and bi-grams/tri-grams creation) before modeling.
- **Training and Tuning:** We explore different configurations of the number of topics and soruce dataset for comparison between the 2 learnign algorithms. For tuning, we optimizaed for cohehernce score.
  - Train LDA model using Variational Inference with Gensim.
  - Train LDA model using Gibbs Sampling with Mallet.
- **Evaluation:** The performance of the algorithms is evaluated using the intrusion test, leveraging Large Language Models (LLM) to assess topic quality.

## Authors

This project was created by Sicun Chen and Ayush Hate.

## References

This section includes references to key documentation and tutorials that heled us in this project:

1. **Gensim LDA Documentation** - Documentation on using Gensim for topic modeling. [Gensim LDA](https://radimrehurek.com/gensim/models/ldamodel.html)
2. **Gensim Coherence Documentation** - Documentation on using Gensim for Coherence calculation. [Gensim Coherence](https://radimrehurek.com/gensim/models/coherencemodel.html)
3. **Gensim Tutorial** - Tutorial using Gensim for topic modeling. [Gensim Tutorial](https://radimrehurek.com/gensim/auto_examples/tutorials/run_lda.html)
4. **Gensim LDA Tips** - A discussion on hyper-parameter setting for Gensim. [Gensim LDA: Tips and Tricks](https://miningthedetails.com/blog/python/lda/GensimLDA/)
5. **Mallet Documentation** - Documentation on using Mallet for topic modeling. [Mallet Topic Modeling](https://mimno.github.io/Mallet/topics)
6. **Mallet Tutorial** - Tutorial using Mallet for topic modeling. [Mallet Tutorial](https://programminghistorian.org/en/lessons/topic-modeling-and-mallet#your-first-topic-model)
7. **Mallet Python Wrapper** - We adpated the wrapper fucntions implemented here: [
little-mallet-wrapper](https://github.com/maria-antoniak/little-mallet-wrapper)

These resources are fundamental for understanding the implementation details and enhancing the functionality of the project.
