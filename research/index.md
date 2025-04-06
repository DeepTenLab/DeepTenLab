---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}DeepTenLab Research Focus

DeepTenLab specializes in investigating and developing novel AI models, leveraging advanced mathematical tools, particularly in matrix and tensor analysis. Our research focuses on:

- **Introducing Novel Matrix and Tensor Methods**: Developing innovative techniques and frameworks for a variety of AI applications, including:
  - Feature Extraction
  - Classification
  - Sparse Coding
  - Spectral Clustering
  - Dictionary Learning
  - Subspace Clustering
  - Matrix Completion
  - Deep Learning
  - Inverse Problems
  
- **Generative Models**: Creating state-of-the-art frameworks, such as GANs and Diffusion models, for generative tasks.

- **Image-to-Image Translation**: Advancing models for tasks like style transfer and domain adaptation.

- **Vision Transformers (ViT)**: Exploring transformer-based architectures for computer vision applications.

- **Graph Neural Networks (GNNs)**: Applying GNNs to analyze complex datasets structured as graphs, with a particular focus on cognitive data (e.g., fMRI and EEG). This research aims to uncover insights in neuroscience, cognitive science, and brain-computer interfaces.

{% include section.html %}

## Most Recent

Co-clustering followed by applying recommendations within each user–item cluster is an effective way to enhance recommender systems. This approach reduces sparsity and ensures that users are only recommended items from their respective clusters. Recently, it has been shown that due to the nature of user–item data, items or users often belong to multiple clusters, making fuzzy co-clustering more appropriate. Unfortunately, despite its potential, few fuzzy co-clustering methods have been developed. In this paper, we introduce two novel fuzzy co-clustering methods based on non-negative matrix factorization (NMF) due to the non-negativity of the rating matrix. One method is based on linear NMF, while the other incorporates a conformal mapping called inverse stereographic projection to appropriately compute the existing similarities within NMF. Both methods offer low computational complexity and better quality compared to previous approaches. However, the adjusted method provides a nonlinear factorization that aligns more closely with the nature of the data. Implementation results on different well known datasets and different recommender systems, evaluated using multiple metrics, demonstrate the quality of these methods, with the adjusted method outperforming the other proposed method.

{% include citation.html lookup="A novel fuzzy co-clustering method for recommender systems via inverse stereographic NMF" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
