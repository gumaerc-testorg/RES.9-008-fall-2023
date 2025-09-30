---
content_type: page
description: Seminar contents.
draft: false
title: Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets
uid: 0079c2df-b4a5-4482-a01f-5909bbf1c319
---
**Taught by:** *Emily Mackevicius and Andrew Bahle, MIT*

**Video:** {{% resource_link "eb187685-dcd9-45eb-87b5-273ce22b233c" "Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets" %}} (1:14:24)

**Description:** The ability to identify interpretable, low-dimensional features that capture the dynamics of large-scale neural recordings is a major challenge in neuroscience. Dynamics that include repeated temporal patterns (which we call sequences), are not succinctly captured by traditional dimensionality reduction techniques such as principal components analysis (PCA) and non-negative matrix factorization (NMF). The presence of neural sequences is commonly demonstrated using visual display of trial-averaged firing rates. However, the field suffers from a lack of task-independent, unsupervised tools for consistently identifying sequences directly from neural data, and cross-validating these sequences on held-out data. This tutorial introduces a tool called seqNMF, for unsupervised discovery of temporal sequences in high-dimensional datasets, which extends a convolutional NMF technique. It provides a framework for extracting sequences from a dataset and is easily cross-validated to assess the significance of each extracted factor. This tutorial provides code to apply seqNMF to several neural and behavioral datasets and provides demo code.

**Slides:** {{% resource_link "45bb34a1-6d47-42e7-8e2f-26d8107f14ad" "Unsupervised Discovery of Neural Sequences in Large-Scale Recordings (PDF)" %}}

**Additional Resources:**

- GitHub: {{% resource_link "63cf8478-8672-4a4f-8606-3a9ed9164e65" "Code and datasets" %}} for seqNMF tool and its application to neural data
- Mackevicius, E. L., Bahle, A. H., Williams, A. H., Gu, S., Denissenko, N. I., Goldman, M. S., and Fee, M. S. (2018) {{% resource_link "7b30db79-5188-4d38-9ca6-39e947434ead" "\"Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets, With Applications to Neuroscience.\"" %}} {{% resource_link "ffeb76ea-3d2e-491f-ac6e-e1fdf03a9e4f" "Early version of paper" %}}.