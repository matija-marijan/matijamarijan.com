---
title: "Message Passing Neural Networks for Sound Source Localization"
collection: publications
category: conferences
permalink: /publication/2025-11-24-sound-source-localization
# excerpt: 'This paper is about fixing template issue #693.'
show_excerpt: false
date: 2025-11-24
venue: '33rd Telecommunications Forum TELFOR'
# paperurl: 'https://belbi.bg.ac.rs/wp-content/uploads/2024/07/BelBi2024-Book-of-Abstracts.pdf'
citation: '<b>M. Marijan</b>, M. Bjelić, &quot;Message Passing Neural Networks for Sound Source Localization&quot; <i>33rd Telecommunications Forum TELFOR</i>.'
---

Sound source localization (SSL) is a fundamental problem in audio signal processing. Traditional SSL approaches often degrade in challenging acoustic conditions, while more recent deep learning-based methods struggle to generalize to unseen microphone arrays or to fully exploit the relationships between microphones in an array. We propose Graph-RelNet, a graph-based neural network that extends relation networks with residual graph convolutional layers to regress the direction of arrival (DoA) from generalized cross-correlation with phase transform (GCC-PHAT) features. Experiments on the TIMIT speech corpus demonstrate that Graph-RelNet consistently outperforms a regression-based adaptation of GNN-SSL, while also surpassing conventional steered response power (SRP) with delay-and-sum (D&S) beamforming at medium and high signal-to-noise ratios (SNRs), especially in scenarios with few microphones. At 5 microphones and SNR = 30 dB, Graph-RelNet reduces mean absolute DoA error by up to 45%. The model also shows strong generalization to unseen microphone arrays and remains competitive under low-SNR conditions.