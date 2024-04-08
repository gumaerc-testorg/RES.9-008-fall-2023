---
content_type: page
description: Seminar contents.
draft: false
title: Calcium Imaging Data Cell Extraction
uid: 5de973fa-d7b0-410f-8ed8-2cced3545899
---
**Taught by:** *Pengcheng Zhou, Columbia University (July 12, 2017)*

**Video:** {{% resource_link "ca037c4b-415d-48df-b0e5-2a93668a899a" "Calcium Imaging Data Cell Extraction" %}}  (1:07:56) \[recording cut short due to technical issues\]

**Description:** In vivo calcium imaging through microendoscopic lenses enables imaging of previously inaccessible neuronal populations deep in the brains of freely moving animals. It is computationally challenging to extract single-neuron activity from microendoscopic data, because of the very large background fluctuations and high spatial overlaps intrinsic to this recording modality. A new matrix factorization approach, named {{% resource_link "7d48b288-00a3-452b-af50-35af65d8847f" "CNMF-E" %}}, was developed to accurately separate the background and then simultaneously demix and denoise the neuronal signals of interest. This method has been thoroughly compared with widely used approaches based on independent components analysis and constrained nonnegative matrix factorization. On both simulated and experimental data, CBMF-E substantially improved the quality of extracted cellular signals and detected more well-isolated neural signals, especially in noisy data. This can in turn significantly enhance the statistical power of downstream analyses and ultimately improve scientific conclusions derived from microendoscopic data. This tutorial reviews existing methods to extract neurons from raw calcium imaging video data and then elaborates on the analysis of microendoscopic data using in implementation of {{% resource_link "21b99f3a-4547-4f9b-81dd-24478d04b08e" "CNMF-E in MATLAB" %}}. The method is specialized for, but not limited to, 1-photon microendoscopic data. In practice, it has also been successfully applied to 2-photon imaging data.

**Slides:** {{% resource_link "804a150b-aeb2-47e2-a342-ecc7c6bafaea" "Calcium Imaging Data Cell Extraction (PDF)" %}}

**Additional Resources:**

- Zhou, P. et al. (2017) {{% resource_link "4e2cd3a0-d441-489e-931c-12213c966270" "Efficient and accurate extraction of in vivo calcium signals from microendoscopic video data" %}}.
- GitHub: {{% resource_link "21b99f3a-4547-4f9b-81dd-24478d04b08e" "Calcium imaging code and exercises in MATLAB" %}}