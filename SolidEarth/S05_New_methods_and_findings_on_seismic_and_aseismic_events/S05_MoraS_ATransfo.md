---
layout: home
title: "A Transformer-Based Classification System for Volcanic Seismic Signals"
---


**Abstract ID**: S05_MoraS_ATransfo

Session ID: [S05](.)

Corresponding author: Cindy Mora-Stock <a href="mailto:cmorasto@uwo.ca">cmorasto@uwo.ca</a>

Coauthors: Alexander Hemming (currently at University of Toronto)
 Cristian Bravo-Roman (University of Western Ontario) 

Volcanic seismic signals are a key element in volcano monitoring to assess the state of unrest and a possible eruption style and timing. Sources such as brittle fracture (volcano-tectonic - VT) or fluid movement (long period - LP) generate signals with distinct characteristics in frequency content and shape, but site effects such as attenuation or background noise make their determination difficult to the untrained eye. In cases of unrest, timely assessment of the seismic evolution provides authorities with the relevant information to prepare or evacuate neighbouring communities; but the amount of data would require a fast and reliable source of pre-classification to catalogue and aid in the job usually done by a human. 
 Transformers are state-of-the-art deep learning methodologies that work with sequence-based data such as audio, text or, in this case, volcanic signals. The power of transformers lies in their ability to identify complex, disconnected patterns and then use them to identify phenomena in a very effective manner. We developed a custom-made Transformer model applying a novel technique of multi-head self-attention (MHSA), used in natural language processing (NLP), to create a deep neural network (DNN) that can automatically classify volcanic events. Our proposed Transformer Encoder model architecture provides minor improvements over existing approaches on pre-processed data. However, when considering raw signals from monitoring stations, our model outperforms existing approaches by a great margin. We tested our model using the Seismic Research Centre's catalogue during the 2020-2021 La Soufriere eruption (Saint Vincent), showing 88% area under receiver operating characteristics curve.

Preferred format: Oral presentation
