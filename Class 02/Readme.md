# Class 02: Foundational Concepts and Statistical Foundations

Welcome to **Class 02: Foundational Concepts and Statistical Foundations**! In this session, we will delve into the essential statistical and probabilistic principles that underpin Generative AI. A strong grasp of these concepts is crucial for understanding how generative models function and how they are evaluated. We will cover probability theory, information theory, evaluation metrics, and an introduction to unsupervised and semi-supervised learning.

---

## Table of Contents

- [Probability Theory and Statistical Foundations](#probability-theory-and-statistical-foundations)
- [Information Theory in Generative Models](#information-theory-in-generative-models)
- [Evaluation Metrics for Generative Models](#evaluation-metrics-for-generative-models)
- [Introduction to Unsupervised and Semi-Supervised Learning](#introduction-to-unsupervised-and-semi-supervised-learning)

---

## Probability Theory and Statistical Foundations

A solid understanding of probability theory is essential for comprehending generative models. These models often rely on probabilistic frameworks to generate new data instances that resemble the training data.

- **Basic Probability Concepts:**
  - **Distributions:** Understanding different probability distributions (e.g., Gaussian, Bernoulli).
  - **Expectation and Variance:** Measures of central tendency and dispersion.
  - **Bayesian Inference:** Updating beliefs based on new evidence.

- **Bayesian Inference in Generative Models:**
  - **Posterior Distribution:** Calculating \( P(\theta | X) \) where \( \theta \) are model parameters and \( X \) is data.
  - **Prior and Likelihood:** Incorporating prior knowledge and data likelihood into model training.

- **Markov Chains:**
  - **Definition:** A sequence of random variables where the future state depends only on the current state.
  - **Applications:** Used in models like Hidden Markov Models (HMMs) and certain types of GANs.

---

## Information Theory in Generative Models

Information theory provides the tools to quantify information within data, which is crucial for evaluating and training generative models.

- **Entropy:**
  - **Definition:** Measures the uncertainty or randomness in a probability distribution.
  - **Role in Generative Models:** Helps in understanding the complexity of the data distribution.

- **Mutual Information:**
  - **Definition:** Measures the amount of information shared between two variables.
  - **Application:** Used to ensure that the generated data retains relevant information from the original data.

- **Kullback-Leibler (KL) Divergence:**
  - **Definition:** Measures the difference between two probability distributions.
  - **Usage:** Often used in VAEs to ensure that the learned distribution is close to the prior distribution.

- **Information Bottleneck Principle:**
  - **Concept:** Balances the trade-off between compression and relevance in representation learning.
  - **Application:** Guides the training of models to retain essential information while discarding noise.

---

## Evaluation Metrics for Generative Models

Assessing the performance of generative models requires specialized metrics that can capture the quality and diversity of the generated data.

- **Inception Score (IS):**
  - **Purpose:** Measures both the quality and diversity of generated images.
  - **Calculation:** Uses a pre-trained Inception network to evaluate the clarity and variety of images.

- **Frechet Inception Distance (FID):**
  - **Purpose:** Evaluates the similarity between generated and real data distributions.
  - **Calculation:** Compares the mean and covariance of feature representations from real and generated images.

- **BLEU Score:**
  - **Purpose:** Evaluates the quality of text generated by models by comparing it to reference texts.
  - **Application:** Commonly used in machine translation and text generation tasks.

- **Perplexity:**
  - **Purpose:** Measures how well a probability model predicts a sample.
  - **Usage:** Often used in language modeling to assess the predictive performance of generative models.

- **Human Evaluation:**
  - **Purpose:** Subjective assessment of the quality and realism of generated content.
  - **Application:** Used alongside quantitative metrics to provide a comprehensive evaluation.

---

## Introduction to Unsupervised and Semi-Supervised Learning

Generative models often operate within unsupervised or semi-supervised learning frameworks, leveraging unlabeled data to enhance their capabilities.

- **Unsupervised Learning:**
  - **Clustering:** Grouping similar data points together without predefined labels.
  - **Dimensionality Reduction:** Reducing the number of random variables under consideration (e.g., PCA, t-SNE).

- **Applications in Generative AI:**
  - **Data Augmentation:** Generating additional training data to improve model performance.
  - **Feature Learning:** Learning meaningful representations of data without explicit labels.

- **Semi-Supervised Learning:**
  - **Definition:** Combines a small amount of labeled data with a large amount of unlabeled data during training.
  - **Benefits:** Improves model performance when labeled data is scarce or expensive to obtain.
  - **Approaches:** Techniques like pseudo-labeling and consistency regularization.

---