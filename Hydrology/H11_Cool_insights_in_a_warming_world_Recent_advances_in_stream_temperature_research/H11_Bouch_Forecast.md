---
layout: home
title: "Forecasting the St-Lawrence River water temperature and freeze-up using Machine Learning"
---


**Abstract ID**: H11_Bouch_Forecast

Session ID: [H11](.)

Corresponding author: Amélie Bouchat <a href="mailto:amelie.bouchat@mcgill.ca">amelie.bouchat@mcgill.ca</a>

Coauthors: Amélie Bouchat1, Bruno Tremblay1, Philippe Lamontagne2, Jean-François Lemieux3, Annika Ogilvie4
 
 1 McGill University, Montreal, Canada; 
 2 National Research Council of Canada, Ottawa, Canada; 
 3 Environnement et Changement Climatique Canada, Dorval, Canada
 4 Fednav Limited, Montreal, Canada; 

Seasonal ice forecasts are necessary to plan shipping operations and ensure safe navigation in icing rivers. However, they are almost non-existent for the St-Lawrence Seaway, a major shipping channel in Canada. To address this, we investigate sources of predictability for the St-Lawrence River freeze-up date (FUD) near Montreal. We find that, in addition to air temperature, the accumulated snowfall in early winter is significantly correlated with observed FUD anomalies. We also show that correlation with water temperature anomalies occurs only at short lead times (weeks), suggesting that the river warming/cooling controlling the FUD variability is likely associated with passing fronts rather than from seasonal pre-conditioning of upstream conditions or climatic variability. In this case, skillful atmospheric forecasts at longer lead times are necessary to forecast the FUD at seasonal time scales. Here, we investigate the use of Machine Learning as a tool to extract signal from seasonal atmospheric forecasts and generate sub-seasonal forecasts of river water temperature and FUD. We build an Encoder-Decoder LSTM model that uses time series of past weather predictors and daily atmospheric forecasts as inputs and returns a forecast of daily water temperature time for the next 60 days. In a perfect forecast experiment (i.e. atmospheric forecasts are replaced with observations), the model can achieve a mean absolute error under 0.8 °C over lead times of 1-60 days. We discuss the limitations of the model near the freeze-up timing and present preliminary results using SEAS5 daily atmospheric forecasts in a real-world forecast experiment.

Preferred format: Either oral or poster
