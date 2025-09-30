---
content_type: page
description: Seminar contents.
draft: false
title: 'GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates'
uid: bb9c9cf5-1575-46d8-9603-b8c97adb26dc
---
**Taught by:** *Jacob Prince, MIT (April 28, 2022)*

**Video:** {{% resource_link "f2a517b2-aaf0-49dd-b821-97e1276a9f03" "GLMsingle: A Toolbox for Improving Single-Trial fMRI Response Estimates" %}}

**Description:** Advances in modern artificial intelligence have inspired a paradigm shift in human neuroscience, yielding large-scale functional magnetic resonance imaging (fMRI) datasets that provide high-resolution brain responses to tens of thousands of naturalistic visual stimuli. Because such experiments necessarily involve brief stimulus durations and few repetitions of each stimulus, achieving sufficient signal-to-noise ratio can be a major challenge. This tutorial will introduce GLMsingle, a scalable, user-friendly toolbox available in MATLAB and Python that enables accurate estimation of single-trial fMRI responses ({{% resource_link "16950227-be92-491f-8524-fe4def7e49fa" "glmsingle.org" %}}). Requiring only fMRI time-series data and a design matrix as inputs, GLMsingle integrates three techniques for improving the accuracy of trial-wise general linear model (GLM) beta estimates. First, for each voxel, a custom hemodynamic response function (HRF) is identified from a library of candidate functions. Second, cross-validation is used to derive a set of noise regressors from voxels unrelated to the experimental paradigm. Third, to improve the stability of beta estimates for closely spaced trials, betas are regularized on a voxel-wise basis using ridge regression. Validation analyses show that GLMsingle substantially improves the reliability of beta estimates across a visually responsive cortex and that these improvements translate into tangible benefits for higher-level analyses relevant to systems and cognitive neuroscience. 

This tutorial will provide a practical overview of GLMsingle, aimed at making the toolbox accessible to a wide range of fMRI users. We will review key concepts in GLM modeling of fMRI data, discuss how the different components of GLMsingle seek to optimize different steps in the signal estimation procedure and walk users through a Google Colab demo illustrating the ease of applying GLMsingle to example fMRI data.

**Additional Resources:**

- {{% resource_link "49a37a46-5955-4337-99fa-99a58d79d747" "Slides" %}}
- {{% resource_link "a6ad1af1-04fd-4cb3-8ae9-8cc3f69f6c4c" "GitHub repository" %}}
- {{% resource_link "eea24fb0-8a3a-43df-bac0-d038184e1291" "Preprint" %}}
- {{% resource_link "300eed8d-e7fe-44d4-89fe-adad55a13953" "Example scripts" %}}