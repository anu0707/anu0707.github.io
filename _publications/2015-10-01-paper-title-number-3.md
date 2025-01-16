---
title: "Exploring the Impact of Different Approaches for Spoken Dialect Identification of Konkani Language"
collection: publications
category: conferences
#permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper solves the problem of dialect identification for Konkani langugage. It involves using BNF and wav2vec 2.0 features to capture acoustic-phonetic characteristics and using TDNN based x-vector, BLSTM based u-vector and Transformer-based u-vector as utterance-level representations that are used as input to the classifier to perform the task of dialect identification.'
date: 2023-12-02
venue: 'International Conference on Speech and Computer (SPECOM), Hubali, Dharwad, India'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Angra Ananya, Sean Monteiro, Muralikrishna H., Veena Thenkanidiyoor, and A. D. Dileep. “Exploring the Impact of Different Approaches for Spoken Dialect Identification of Konkani Language.” In International Conference on Speech and Computer, pp. 461-474. Cham: Springer Nature Switzerland, 2023.'
---

his work aims to identify dialects for Konkani language. In this work, various state-of-the-art methods in language identification are explored for the identification of dialects of the Konkani language. The initial base model is constructed using fully connected neural network which is trained on frame-level Mel-frequency cepstral coefficient (MFCC) features. This base model trained on frame-level features is then used for comparison with state-of-the-art models from language identification task that are built for dialect identification (DID) that use utterance-level embeddings, namely x-vector and u-vector. The x-vector and u-vector based models are trained on segment-level features. This work explores segment-level features namely phone-state bottleneck features (BNFs) and wav2vec features extracted from pretrained feature extractors. The x-vector based model uses time delay neural network (TDNN) for the extraction of an utterance-level embedding from sequence of speech segments. A u-vector based model uses bidirectional LSTM (BLSTM) to extract utterance-level embeddings from sequence of speech segments. This work also proposes a novel transformer-based model to extract utterance-level embedding from sequence of speech segments. Results show the effectiveness of the proposed methods for DID of Konkani. It is observed that proposed transformer-based model outperform the other explored models. The results also show the superiority of wav2vec features over the phone-state BNFs for DID task.
