---
content_type: page
description: Seminar contents.
draft: false
title: Decoding Animal Behavior through Pose Tracking
uid: 5e0c8e8c-96af-4be2-821f-b6daf77b54da
---
**Taught by:** *Talmo Pereira, Princeton University (July 9, 2020)*

**Video:** {{% resource_link "321fedf8-9e4b-4581-8e66-f9c676e587a7" "Decoding Animal Behavior through Pose Tracking" %}}

**Description:**

Behavioral quantification, the problem of measuring and describing how an animal interacts with the world, has been gaining increasing attention across disciplines as new computational methods emerge to automate this task and increase the expressiveness of these descriptions. In neuroscience, understanding behavior is crucial to interpretation of the structure and function of biological neural circuits, but tools to measure what an animal is doing have lagged behind the ability to record and manipulate neural activity.

In order to get a handle on how neural computations enable animals to produce complex behaviors, we turn to pose tracking in high-speed videography as a means of measuring how the brain controls the body. By quantifying the movement patterns of the humble fruit fly, we demonstrate how advances in computer vision and deep learning can be leveraged to describe the "body language" of freely moving animals. We further demonstrate that these techniques can be applied to a diverse range of animals, ranging from bees and flies to mice and giraffes.

This talk will describe our work in generalizing deep learning-based methods developed for human pose estimation to the domain of animals. We tackle the problems of learning with few labeled examples, dataset-tailored neural network architecture design, and multi-instance pose tracking to build a general-purpose framework for studying animal behavior. Finally, we'll explore how postural dynamics can be used in unsupervised action recognition to create interpretable descriptions of unconstrained behavior.

{{% resource_link "db656c46-4673-4f0c-9649-64a4fd06c1fd" "Slides, code, and data for tutorial (GitHub)" %}}

In the tutorial part of the session, we will work through the usage of our framework SLEAP ({{% resource_link "ae228482-9463-4861-8ffb-889095c90dc9" "https://sleap.ai" %}}) to see how we can train and evaluate deep learning models for animal pose tracking right in the browser. No data is required but we will provide a short tutorial on using SLEAP with your own data for which a laptop with {{% resource_link "b300fc47-7e11-4bdf-b84b-38226d7816e3" "Miniconda" %}} installed is recommended.

**Speaker Bio:** Talmo Pereira is a PhD candidate in Neuroscience at Princeton University where he uses deep learning and computer vision to develop new tools for studying animal behavior. His recent work has demonstrated how advances in deep learning-based human pose estimation and tracking can be adapted to the domain of animals to solve problems in fields ranging from neuroscience to ecology. This work has been published in *Nature Methods* and featured in *The Scientist*, *Nature Lab Animal*, *Nature Toolbox*, and *Quanta* magazine. Talmo was a research intern in Perception at Google AI working on pose-based action recognition, an NSF Graduate Research Fellow, and was recently a recipient of the Porter Ogden Jacobus Fellowship, Princeton University's top graduate student honor.