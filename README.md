# **Sequence-to-sequence Transformer based Text Summarization with PEGASUS**

PEGASUS, or Pre-training with Extracted Gap-sentences for Abstractive Summarization Sequence-to-sequence models, uses self-supervised objective Gap Sentences Generation (GSG) to train a transformer encoder-decoder model.

In this project, we will explore various pre-trained models built on the Pegasus architecture, each of which has demonstrated state-of-the-art results in specific summarization tasks. These models include Pegasus-XSUM, Pegasus-CNN/DailyMail, Pegasus-WikiHow, Pegasus-BigPatent, and Pegasus-arXiv. For each model, we will outline its core features, the datasets it was trained on, and its performance on corresponding benchmarks. After evaluating these models, we will fine-tune the Pegasus model on the AESLC dataset and compare the resulting metrics to assess its effectiveness.

This repository documents my experimental research and implementations exploring the PEGASUS text summarization model. It serves as a comprehensive learning resource, incorporating insights and code references from multiple academic and technical sources. All studies, code implementations, and referenced materials are attributed to their respective original creators and owners.


References and Sources : 
1. arXiv:1912.08777v3 [cs.CL] | PEGASUS: Pre-training with Extracted Gap-sentences for Abstractive Summarization by Jingqing Zhang, Yao Zhao, Mohammad Saleh, Peter J. Liu
2. https://github.com/google-research/pegasus
3. https://github.com/Tuhin-SnapD/Text-Summarization-Models/blob/main/Models%20Used%20in%20Proposed%20Architecture/all-12-pegasus-models.ipynb
4. CNN/DailyMail Finetuning : https://github.com/jankovidakovic/pegasus-fine-tuning

