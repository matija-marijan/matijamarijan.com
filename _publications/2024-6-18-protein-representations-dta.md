---
title: "Impact of Protein Representations on Drug–Target Affinity Prediction"
collection: publications
category: conferences
permalink: /publication/2024-6-18-protein-representations-dta
# excerpt: 'This paper is about fixing template issue #693.'
show_excerpt: false
date: 2024-06-18
venue: '5th Belgrade Bioinformatics Conference'
paperurl: 'https://belbi.bg.ac.rs/wp-content/uploads/2024/07/BelBi2024-Book-of-Abstracts.pdf'
citation: '<b>M. Marijan</b>, I. Tanasijević, &quot;Impact of Protein Representations on Drug–Target Affinity Prediction&quot; <i>5th Belgrade Bioinformatics Conference</i>.'
---

Accurate and rapid prediction of the binding affinity between potential drug candidates
and target proteins can significantly hasten the drug discovery and development process.
Utilizing artificial intelligence (AI) models to predict drug-target affinity (DTA) is an affordable
and efficient strategy for sifting out undesirable molecules and identifying promising drug
candidates. This approach allows researchers to focus on the most promising compounds
for further in silico and wet lab experiments, thereby streamlining the overall workflow.
Advancements in AI research, such as the development and implementation of graph
neural networks (GNN) and attention mechanisms, have significantly improved methods
for processing small molecules as potential drug candidates. These developments now
allow for very efficient and accurate DTA prediction, without the need for extensive protein
processing resources. While this progress marks a significant step forward in computational
drug discovery, models that heavily rely on efficient molecule processing may still lack the
incorporation of highly specific protein information into their algorithms, which could be
crucial for further improvement.
In this study, we present a comprehensive analysis of the impact of different protein
representations on the accuracy of DTA prediction using two datasets, by implementing and
modifying AI models that are based on GNNs and large language models (LLM).
Motivated by the intuitive resemblance between traditional motif search methods for protein
sequence analysis and conventional one-dimensional convolution in AI signal processing,
we propose a protein representation model based on transposed convolutional neural
network (NN) layers. Preliminary results indicate that such embeddings improve the overall
affinity prediction accuracy, compared to similar models from the literature. Additionally,
implementing LLMs to generate protein embeddings independently of other NN layers has
demonstrated potential to significantly enhance the accuracy of predicting drug-target pairs
that have a very low or unmeasurable affinity.