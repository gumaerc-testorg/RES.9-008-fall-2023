---
content_type: page
description: Tutorial contents.
draft: false
title: Tutorial on Statistical Inference on Representational Geometries
uid: e7e9e217-72b6-483e-8468-272f181a80e8
---
**Taught by:** *Heiko Schütt, NYU (October 25, 2022)*

**Video:** {{% resource_link "5271cb80-aded-44cb-a8f0-8cf16e851c10" "Tutorial on Statistical Inference on Representational Geometries" %}}

**Description:** Representational similarity analysis (RSA) is a popular method for comparing representations when a mapping between them is not available. One important comparison RSA is used for is between neuronal measurements and models of brain computation like deep neural networks. RSA is a two-step process. First, a matrix of pairwise dissimilarities between conditions is computed. This matrix is then a summary of the representational geometry, which can be compared directly between different representations as it has the same dimensions. In the first half of this tutorial, I will go through some recent advancements for RSA that improve the reliability and statistical accuracy of RSA substantially: First, I will explain the reasoning for cross-validated distance measures for computing the dissimilarity matrix and for whitened similarity measures to compare them to each other. Then, I will explain why simultaneous generalization to new subjects and new stimuli is hard and a solution based on bootstrapping. Finally, I will explain the necessary cross-validation-based extensions for flexible models. In the second half of this tutorial, I will give a guide on how to run these analyses using our new *rsatoolbox* in Python by going through demo notebooks that illustrate the functionality.

**Additional Resources**:

Relevant papers:

- Schütt et al., 2021: {{% resource_link "80181cc3-159c-47e0-b01a-42c9253366eb" "\"Statistical Inference on Representational Geometries.\"" %}} arXiv:2112.09200.
- Walther et al., 2016: {{% resource_link "ec11d6e8-c966-4aa1-9550-2a3e1beafc53" "\"Reliability of Dissimilarity Measures for Multi-voxel Pattern Analysis.\"" %}} *Neuroimage* 137: 188–200.
- Diedrichsen et al., 2021: {{% resource_link "fac43027-64d0-415b-a33b-48f19b8bf4c2" "\"Comparing Representational Geometries Using Whitened Unbiased-Distance-Matrix Similarity.\"" %}} arXiv:2007.02789.

GitHub Repositories:

- {{% resource_link "a7300d37-4eb8-43c1-98cc-5fffcbcb8897" "GitHub repository" %}}
- {{% resource_link "4f0050b8-f9f4-40d0-b45b-85f72e063dee" "GitHub demo repository" %}}