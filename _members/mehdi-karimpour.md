---
name: Mehdi Karimpour
aliases:
  - M Karimpour
image: images/photo.jpg
role: postdoc
group: postdoc
links:
  email: mkarimpoursb@yahoo.com
  google-scholar: 5xzJu_cAAAAJ
  orchid: 0000-0002-5584-8020
---

I am a postdoctoral researcher at the School of Computer Science, Tarbiat Modares University, under the supervision of Dr. Mansoor Rezghi, supported by INSF. My research background lies in numerical linear algebra and matrix computations, with a particular focus on developing and implementing iterative algorithms for solving linear systems arising from image reconstruction problems.

During my postdoctoral research, I am working on non-negative matrix factorization (NMF) methods and their applications in learning tasks. Over the past two decades, NMF has gained significant attention in data mining and machine learning due to its effectiveness in uncovering latent structures in data. It has been successfully applied in various fields, including clustering, computer vision, signal processing, community detection, and social media analysis.

As part of my research, we successfully developed a novel NMF solver based on block column iterations [1]. Additionally, in a recently published paper [2], we introduced an innovative unsupervised deep non-negative matrix factorization network for feature extraction from two-dimensional data. While NMF has proven to be a powerful tool for dimensionality reduction and learning tasks, its conventional and deep versions are inherently vector-based, meaning they can only process one-dimensional data. Consequently, two-dimensional data, such as images, must be reshaped into vectors before applying these methods. This vectorization process disrupts the spatial relationships between features, increases computational complexity, and heightens the risk of overfitting.

To overcome these limitations, our paper proposes a double-sided NMF model that preserves the original structure of the data, unlike traditional NMF approaches. By maintaining the spatial relationships of features, our method reduces the number of parameters and computational complexity while enhancing efficiency. Furthermore, we introduce two deep variations—linear and nonlinear—designed to extract hierarchical features from data. We evaluate the clustering performance of our methods on two real-world image datasets and compare them with conventional vector-based NMF and deep NMF techniques. Numerical experiments confirm that our proposed algorithms offer superior performance and efficiency.

[1]-M. Karimpour, M. rezghi,  A block column iteration for nonnegative matrix factorization, Journal of Computational Science, 64, 2022.
[2]- M. karimpour, M. rezghi, A double-sided deep nonnegative matrix factorization network for feature extraction of two dimensional data, Expert systems with applications, 271, 2025.
