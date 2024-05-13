---
title: "Subpopulation-Specific Synthetic EHR for Better Mortality Prediction"
collection: publications
permalink: /publication/bias
excerpt: 'Electronic health records (EHR) often contain different rates of representation of certain subpopulations (SP). Factors like patient demographics, clinical condition prevalence, and medical center type contribute to this underrepresentation. Consequently, when training machine learning models on such datasets, the models struggle to generalize well and perform poorly on underrepresented SPs. To address this issue, we propose a novel ensemble framework that utilizes generative models. Specifically, we train a GAN-based synthetic data generator for each SP and incorporate synthetic samples into each SP training set. Ultimately, we train SP-specific prediction models. To properly evaluate this method, we design an evaluation pipeline with 2 real-world use case datasets, queried from the MIMIC database. Our approach shows increased model performance over underrepresented SPs. Our code and models are given as supplementary and will be made available on a public repository.'
date: 2023-01-01
venue: '22nd Internation Conference on Artificial Intelligence in Medicine (AIME)'
paperurl: 'https://arxiv.org/abs/2305.16363'
citation: 'Perets, O., & Rappoport, N. (2023). Ensemble Synthetic EHR Generation for Increasing Subpopulation Model's Performance. arXiv preprint arXiv:2305.16363.'
---
