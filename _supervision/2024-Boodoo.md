---
title: "Fadil Boodoo"
excerpt: "Contribution of Artificial intelligence to spatio-temporal flood forecasting"
collection: supervision
---




**University of Montpellier**, 2024.

**Supervisors**: C. Delenne (50%), R. Hostache (50%).
[ORCID](https://orcid.org/0000-0002-7469-9366); [theses.fr/s308004](https://www.theses.fr/s308004).


*"Contribution of Artificial intelligence to spatio-temporal flood forecasting"*

**Abstract**
In the current context of increasing flood risks driven by climate change, the accurate and timely prediction of inundations has become a critical challenge for operational risk management. This thesis investigates the potential of artificial intelligence (AI) methods - particularly recurrent neural networks (LSTM) and graph neural networks (GNN) - to enhance hydrological and hydraulic modelling. First, the study assesses the sensitivity of LSTM model performance to the duration and diversity of training data, in comparison with a traditional conceptual rainfall-runoff model, Superflex. While LSTMs outperform the conceptual model when trained on abundant and representative data - reaching a Nash-Sutcliffe Efficiency (NSE) coefficient of 0.89 - they exhibit significant performance degradation under limited-data scenarios, with an average NSE drop of 0.14. This effect is not observed in Superflex, raising critical concerns about the robustness of LSTM models under future climate variability. In the second part, an innovative graph neural network model, named HydroGCN, is developed to predict water levels from discharge data by leveraging the topological structure of hydraulic systems. Evaluated on both a synthetic canal and the real Severn River basin in the UK, HydroGCN shows a remarkable ability to replicate the dynamics simulated by the reference physical model SW2D, achieving an NSE of 0.99 while enabling a reduction of computation time by a factor of more than 80. This work highlights the value of explicitly modelling spatial relationships through graphs, while also identifying key areas for improvement, such as incorporating bidirectional interactions and enriching the physical attributes used. This research thus paves the way for a new generation of flood forecasting tools that combine speed, accuracy, and adaptability. It also underscores the importance of developing innovative evaluation methodologies that are essential to ensure the robustness of AI models in a changing climate, ultimately enabling the emergence of truly operational solutions for future flood risk management.