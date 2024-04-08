---
content_type: page
description: Tutorial contents.
draft: false
title: Tutorial on Statistical Inference on Representational Geometries
uid: e7e9e217-72b6-483e-8468-272f181a80e8
---
**Taught by:** *Heiko Schütt, NYU (October 25, 2022)*

**Video:** {{% resource_link "000b9841-cfa6-4658-8305-6a562232dd71" "Tutorial on Statistical Inference on Representational Geometries" %}}

**Description:** Representational similarity analysis (RSA) is a popular method for comparing representations when a mapping between them is not available. One important comparison RSA is used for is between neuronal measurements and models of brain computation like deep neural networks. RSA is a two-step process. First, a matrix of pairwise dissimilarities between conditions is computed. This matrix is then a summary of the representational geometry, which can be compared directly between different representations as it has the same dimensions. In the first half of this tutorial, I will go through some recent advancements for RSA that improve the reliability and statistical accuracy of RSA substantially: First, I will explain the reasoning for cross-validated distance measures for computing the dissimilarity matrix and for whitened similarity measures to compare them to each other. Then, I will explain why simultaneous generalization to new subjects and new stimuli is hard and a solution based on bootstrapping. Finally, I will explain the necessary cross-validation-based extensions for flexible models. In the second half of this tutorial, I will give a guide on how to run these analyses using our new *rsatoolbox* in Python by going through demo notebooks that illustrate the functionality.

**Additional Resources**:

Relevant papers:

- Schütt et al., 2021: {{% resource_link "bdb535c1-39bb-413f-bcc2-33a433a2594b" "\"Statistical Inference on Representational Geometries.\"" %}} arXiv:2112.09200.
- Walther et al., 2016: {{% resource_link "fabb7ef1-a4d3-4506-8921-72a964718f25" "\"Reliability of Dissimilarity Measures for Multi-voxel Pattern Analysis.\"" %}} *Neuroimage* 137: 188–200.
- Diedrichsen et al., 2021: {{% resource_link "6c236a3e-2416-4497-9834-951c2f9f19bf" "\"Comparing Representational Geometries Using Whitened Unbiased-Distance-Matrix Similarity.\"" %}} arXiv:2007.02789.

GitHub Repositories:

- {{% resource_link "7aa617f6-2c79-4dd5-b83f-6c4568e52a90" "GitHub repository" %}}
- {{% resource_link "e2b8e8c2-ab8a-4966-8c80-d49642146d90" "GitHub demo repository" %}}