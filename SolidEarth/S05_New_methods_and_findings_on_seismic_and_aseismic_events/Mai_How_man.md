---
layout: home
title: ""How many waveforms do I need?" Understanding how the architecture of seismic datasets affects the performance of deep learning models for automated phase-picking."
---


Corresponding author: Hao Mai: hmai090@uottawa.ca

Coauthors: Pascal Audet, University of Ottawa
 Claire Perry, Canadian Hazards Information Service, Natural Resources Canada
 Clément Estève, University of Vienna 

The use of deep learning (DL) in earthquake detection and phase-picking tasks has produced impressive results in recent years. Driven by large seismic datasets, DL pickers and transfer learning pickers hold much promise in improving the accuracy of automated picks. However, the applications of these pickers to new target regions are at risk of failing if the seismic data distribution differs from the original training datasets. In addition, transfer learning may suffer in regions where reliable, human-reviewed waveforms are sparse. The challenges for seismologists are in 1) determining how many waveforms are required for the model training in order to achieve their desired phase-picking accuracy, and 2). which proposed DL pickers can be applied directly to a region without re-training. In this study, we explore the issues of deep learning model performance by progressively increasing sample sizes and examining various data distribution scenarios during training. This will help seismologists in the optimal allocation of resources, labour, and efficient study design. To this end, we re-train two DL pickers, Phase-Net and EQTransformer, using four different training datasets of varying size (500, 1000, 10,000, and 100,000) to test the phase-picking accuracy with the same validation set. We also directly apply pre-trained models to evaluate whether they are suitable in the same situation. From this experiment, we gain insight into how many waveforms should be adopted in a new DL project and what other factors (e.g., signal-to-noise ratio, magnitude range, etc.) might impact training and model performance. Our study provides a guide for determining the optimal size of the training data set and model selection for future studies.

Preferred format: Oral presentation
