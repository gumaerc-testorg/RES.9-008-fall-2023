---
content_type: page
description: Seminar contents.
draft: false
title: Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets
uid: 0079c2df-b4a5-4482-a01f-5909bbf1c319
---
**Taught by:** *Emily Mackevicius and Andrew Bahle, MIT*

**Video:** {{% resource_link "518fef00-3705-402b-a2bd-6dbbdbfe4032" "Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets" %}} (1:14:24)

**Description:** The ability to identify interpretable, low-dimensional features that capture the dynamics of large-scale neural recordings is a major challenge in neuroscience. Dynamics that include repeated temporal patterns (which we call sequences), are not succinctly captured by traditional dimensionality reduction techniques such as principal components analysis (PCA) and non-negative matrix factorization (NMF). The presence of neural sequences is commonly demonstrated using visual display of trial-averaged firing rates. However, the field suffers from a lack of task-independent, unsupervised tools for consistently identifying sequences directly from neural data, and cross-validating these sequences on held-out data. This tutorial introduces a tool called seqNMF, for unsupervised discovery of temporal sequences in high-dimensional datasets, which extends a convolutional NMF technique. It provides a framework for extracting sequences from a dataset and is easily cross-validated to assess the significance of each extracted factor. This tutorial provides code to apply seqNMF to several neural and behavioral datasets and provides demo code.

**Slides:** {{% resource_link "ee8dd5bb-0e26-4754-be0a-3caf534bdc8a" "Unsupervised Discovery of Neural Sequences in Large-Scale Recordings (PDF)" %}}

**Additional Resources:**

- GitHub: {{% resource_link "35669969-71fc-4d62-9e64-9bc83b993b06" "Code and datasets" %}} for seqNMF tool and its application to neural data
- Mackevicius, E. L., Bahle, A. H., Williams, A. H., Gu, S., Denissenko, N. I., Goldman, M. S., and Fee, M. S. (2018) {{% resource_link "9bf7c7e5-a716-4717-873c-db17f015f44d" "\"Unsupervised Discovery of Temporal Sequences in High-Dimensional Datasets, With Applications to Neuroscience.\"" %}} {{% resource_link "89712903-5c9f-4827-8f08-676840ab275f" "Early version of paper" %}}.