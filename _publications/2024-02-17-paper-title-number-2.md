---
title: "Exploring aggregated wav2vec 2.0 features and dual-stream TDNN for efficient spoken dialect identification"
collection: publications
category: manuscript
#permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'In this paper, we obtain representations from various layers of wav2vec 2.0 and aggregate them using various pooling strategies. Pooling is applied across both time and layers to obtain utterance-level representation suitable for the task of spoken dialect identification. We also use recently proposed DS-TDNN to obtain representations suitable for the task of dialect identification.'
#date: 2024-02-17
venue: 'IEEE Access'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'A. Angra, Muralikrishna H., A. D. Dileep, Veena Thenkanidiyoor, “Exploring aggregated wav2vec 2.0 features and dual-stream TDNN for efficient spoken dialect identification” Communicated'
---

Dialect identification (DID) is a challenging task due to high inter-class similarities between the dialects. Efficiency of a DID system depends on how well the input features encode the DID-specific contents in the speech that is spread across the utterance. In this paper, we explore different representations for efficient DID, which are motivated by the recent advancements in related areas. Firstly, we propose to learn a representation by aggregating the layers-wise features from wav2vec 2.0. We propose multiple approaches to combine the layer-wise features. Since different layers of wav2vec 2.0 are known to capture different acoustic-linguistic characteristics, such aggregated representation encode DID-specific contents in a better way. Followed by this, we explore the usage of recently proposed global-aware filter (GAF) layer based dual-stream time delay neural network (DS-TDNN) for DID. The GAF layer employs a set of learnable transform-domain filters between a 1D discrete Fourier transform and its inverse transform to capture global context along with dynamic filtering and sparse regularization. DS-TDNN has two separate input branches, one for capturing global context and the other for local context which are combined in a parallel pattern. Results obtained on dialects of Kannada, Tamil, Konkani and Marathi, four low-resource languages of India show that aggregated wav2vec 2.0 features perform better compared to DS-TDNN approach.
