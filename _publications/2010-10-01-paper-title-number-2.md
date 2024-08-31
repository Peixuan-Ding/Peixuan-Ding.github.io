---
title: "Multitask Learning for Aero-Engine Bearing Fault Diagnosis With Limited Data"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'Authors: Peixuan Ding, Yi Xu, Xi-Ming Sun'
date: 2024-04-30
venue: 'IEEE Transactions on Instrumentation and Measurement'
citation: 'P. Ding, Y. Xu and X. -M. Sun, "Multitask Learning for Aero-Engine Bearing Fault Diagnosis With Limited Data," in IEEE Transactions on Instrumentation and Measurement, vol. 73, pp. 1-11, 2024, Art no. 3520111, doi: 10.1109/TIM.2024.3395323.'
---

Abstract:
Maintaining the operational stability of an aero-engine heavily relies on the health of the rotor bearings. Data-driven fault diagnosis approaches have achieved significant success due to their superior ability to identify faults. However, the application of conventional deep learning methods, which heavily rely on a huge amount of vibration signals, is unrealistic in most aero-engine-related cases due to the limited number of fault samples. To tackle this problem, a multitask Siamese network (MTSN) is proposed, which combines data augmentation (DA) and metric learning into a unified framework. First, in the multiclassification task, a limited number of samples are augmented using Mixup and learned by a convolutional neural network (CNN). Then, in the metric learning task, the similarity between sample pairs is learned by the shared encoder in the Siamese network. To ensure effective learning in both tasks, the loss functions of the two learning tasks are balanced by introducing uncertainty. Based on two public bearing fault datasets, we conducted a series of experiments. The experimental results show that the learning tasks mutually reinforce each other, and the MTSN exhibits good fault diagnosis performance with limited data.
