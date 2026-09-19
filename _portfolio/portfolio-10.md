---
title: "Interpretability Analysis of Bilingual Brain-Informed Fine-Tuning in BERT"
img: /images/bling-tuning.png
imgpx: 900px
link: https://github.com/denizenslab/bling-tuning-interp/tree/main
excerpt: "BERT is a Transformer encoder pretrained with a masked-language-model objective, producing deeply bidirectional contextual representations by conditioning each token on both its left and right context Devlin et al., 2019. In the original brain-informed fine-tuning framework, bilingual participants read naturalistic stories in English and Chinese while their BOLD responses were recorded. Token-level language-model representations are temporally aligned with fMRI responses using differentiable downsampling and haemodynamic delays. A voxelwise prediction head is trained to predict BOLD activity, and the resulting brain-encoding loss is backpropagated through the language model. Thus, the model is tuned to produce representations that better predict bilingual neural responses during naturalistic language comprehension Negi et al., 2025.

The aim of this work is to ask a mechanistic question: what changes inside the model after bilingual brain-informed supervision? We compare fine-tuned variants with their corresponding pretrained base models across syntax-sensitive structure, representational geometry, language-specific output routing, factual retrieval, and causal pathways through layers and attention heads."
collection: portfolio
era: "master"
---
