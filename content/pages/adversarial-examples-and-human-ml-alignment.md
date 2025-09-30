---
content_type: page
description: Seminar contents.
draft: false
title: Adversarial Examples and Human-ML Alignment
uid: 97376f81-d49c-4d8c-bbba-a6e7d4d325a2
---
**Taught by:** *Shibani Santurkar, MIT (July 23, 2020)*

**Video:** {{% resource_link "98c07aa4-8d70-42a5-82e0-fde363358850" "Adversarial Examples and Human-ML Alignment" %}}

**Description:**

Machine learning models today achieve impressive performance on challenging benchmark tasks. Yet these models remain remarkably brittle—small perturbations of natural inputs, known as adversarial examples, can severely degrade their behavior.

Why is this the case?

In this tutorial, we take a closer look at this question and demonstrate that the observed brittleness can be largely attributed to the fact that our models tend to solve classification tasks quite differently from humans. Specifically, viewing neural networks as feature extractors, we study how features extracted by neural networks may diverge from those used by humans, and how adversarially robust models can help to make progress towards bridging this gap.

**Speaker Bio:** Shibani Santurkar is a PhD student in the MIT EECS Department, advised by Aleksander Mądry and Nir Shavit. Her research has been focused on two broad themes: developing a precise understanding of widely-used deep learning techniques; and avenues to make machine learning methods robust and reliable. Prior to joining MIT, she received a bachelor's degree in electrical engineering from IIT Bombay. She is a recipient of the Google Fellowship in Machine Learning.

**Additional Resources:**

The tutorial will include demos—we will use Colab notebooks so please bring laptops along. In these demos, we will explore the brittleness of standard ML models by crafting adversarial perturbations, and use these as a lens to inspect the features models rely on.

{{% resource_link "ff5d4df8-9e41-4afb-9d90-a9972dd11f4e" "Github link for demos" %}}

Suggested reading (in order of importance):

- {{% resource_link "a5e717af-7d14-4a99-8465-fccc599a4f6d" "Adversarial examples" %}}
- {{% resource_link "a5c2b312-a881-4876-bf65-5f77df0fefb7" "Training robust models" %}}
- {{% resource_link "80bf798e-f748-4626-b3c2-6e895698496b" "ML models rely on imperceptible features" %}}
- Robustness as a feature prior
    - {{% resource_link "e6a9df84-6ec2-43ad-9c99-89fca6a16f51" "*Robustness may be at odds with accuracy*" %}}
    - {{% resource_link "d3d3cb93-c106-4568-b139-3747a45180df" "*Adversarial robustness as a prior for learned representations*" %}}