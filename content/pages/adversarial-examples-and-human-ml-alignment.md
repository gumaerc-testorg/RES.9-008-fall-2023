---
content_type: page
description: Seminar contents.
draft: false
title: Adversarial Examples and Human-ML Alignment
uid: 97376f81-d49c-4d8c-bbba-a6e7d4d325a2
---
**Taught by:** *Shibani Santurkar, MIT (July 23, 2020)*

**Video:** {{% resource_link "bb976b84-7c76-490b-8fff-8bb999e18cdb" "Adversarial Examples and Human-ML Alignment" %}}

**Description:**

Machine learning models today achieve impressive performance on challenging benchmark tasks. Yet these models remain remarkably brittle—small perturbations of natural inputs, known as adversarial examples, can severely degrade their behavior.

Why is this the case?

In this tutorial, we take a closer look at this question and demonstrate that the observed brittleness can be largely attributed to the fact that our models tend to solve classification tasks quite differently from humans. Specifically, viewing neural networks as feature extractors, we study how features extracted by neural networks may diverge from those used by humans, and how adversarially robust models can help to make progress towards bridging this gap.

**Speaker Bio:** Shibani Santurkar is a PhD student in the MIT EECS Department, advised by Aleksander Mądry and Nir Shavit. Her research has been focused on two broad themes: developing a precise understanding of widely-used deep learning techniques; and avenues to make machine learning methods robust and reliable. Prior to joining MIT, she received a bachelor's degree in electrical engineering from IIT Bombay. She is a recipient of the Google Fellowship in Machine Learning.

**Additional Resources:**

The tutorial will include demos—we will use Colab notebooks so please bring laptops along. In these demos, we will explore the brittleness of standard ML models by crafting adversarial perturbations, and use these as a lens to inspect the features models rely on.

{{% resource_link "4c06a5da-3b47-4f91-9195-0c25a4e4c29a" "Github link for demos" %}}

Suggested reading (in order of importance):

- {{% resource_link "6cebac93-239a-4c27-82bc-80af097ad885" "Adversarial examples" %}}
- {{% resource_link "26fc7944-9c8e-458e-9b62-9880d4c92bc0" "Training robust models" %}}
- {{% resource_link "c3c74c7b-8bb9-481b-a4a7-016101a7530c" "ML models rely on imperceptible features" %}}
- Robustness as a feature prior
    - {{% resource_link "f3c7c701-5a84-42cb-814c-d53589eade39" "*Robustness may be at odds with accuracy*" %}}
    - {{% resource_link "eccf428e-7c0e-4495-a5f7-3b294b5ec0cf" "*Adversarial robustness as a prior for learned representations*" %}}