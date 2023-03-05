---
layout: home
title: "A novel Deep Network Inversion of Magnetic Anomalies to Estimate Basement Structure"
---


**Abstract ID**: S03_Baghe_AnovelDe

Session ID: [S03](.)

Corresponding author: Zahra Bagheriashena <a href="mailto:zahra.bagheriashena@ucalgary.ca">zahra.bagheriashena@ucalgary.ca</a>

Coauthors: Hojjat Kabirzadeh , University of Calgary; Jeong Woo Kim, University of Calgary; Xin Wang, University of Calgary 

A Deep Neural Network (DNN) inversion technique has been developed to estimate the basement structure using magnetic anomalies. The inherent non-uniqueness and non-linearity flaws of geophysical inversions are addressed using the DNN. A novel approach is used to simulate the training dataset required for training the DNN model. Accordingly, a two-layer forward model of the subsurface is designed as the base model representing sediments, and the basement of the study region. The length and height of the model are determined based on the dimensions of the target area to be investigated. Several random parameters are set to create different representations of the forward model by iteratively changing the depth and shape of the layers. Given the depth of the basement and its pre-defined susceptibility parameter, the magnetic anomaly of each forward model is calculated over a 2D profile. Using multi-processing algorithms, thousands of training samples are simulated comprising magnetic anomalies as input features and depth-to-basement as labels. A DNN model is trained using the simulated dataset to conduct the nonlinear inverse mapping of the magnetic anomaly to the basement topography. Following this, the performance of the trained model is assessed by making predictions on noise-free and noise-contaminated magnetic data. The DNN inversion model is employed to estimate the basement topography of a real case study.

Preferred format: Poster
