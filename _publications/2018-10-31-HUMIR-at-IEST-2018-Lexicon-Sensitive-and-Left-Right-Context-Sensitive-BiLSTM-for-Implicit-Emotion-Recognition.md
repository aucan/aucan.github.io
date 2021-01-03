---
title: "HUMIR at IEST-2018: Lexicon-Sensitive and Left-Right Context-Sensitive BiLSTM for Implicit Emotion Recognition"
collection: publications
permalink: /publication/2018-10-31-HUMIR-at-IEST-2018-Lexicon-Sensitive-and-Left-Right-Context-Sensitive-BiLSTM-for-Implicit-Emotion-Recognition
excerpt: ''
date: 2018-10-31
venue: 'Proceedings of the 9th Workshop on Computational Approaches to Subjectivity, Sentiment and Social Media Analysis'
paperurl: 'https://www.aclweb.org/anthology/W18-6225/'
citation: 'Naderalvojoud, B., Ucan, A., & Sezer, E. A. (2018, October). HUMIR at IEST-2018: Lexicon-Sensitive and Left-Right Context-Sensitive BiLSTM for Implicit Emotion Recognition. In Proceedings of the 9th Workshop on Computational Approaches to Subjectivity, Sentiment and Social Media Analysis (pp. 182-188).'
---
This paper describes the approaches used in HUMIR system for the WASSA-2018 shared task on the implicit emotion recognition. The objective of this task is to predict the emotion expressed by the target word that has been excluded from the given tweet. We suppose this task as a word sense disambiguation in which the target word is considered as a synthetic word that can express 6 emotions depending on the context. To predict the correct emotion, we propose a deep neural network model that uses two BiLSTM networks to represent the contexts in the left and right sides of the target word. The BiLSTM outputs achieved from the left and right contexts are considered as context-sensitive features. These features are used in a feed-forward neural network to predict the target word emotion. Besides this approach, we also combine the BiLSTM model with lexicon-based and emotion-based features. Finally, we employ all models in the final system using Bagging ensemble method. We achieved macro F-measure value of 68.8 on the official test set and ranked sixth out of 30 participants.

[Download paper here](https://www.aclweb.org/anthology/W18-6225/)

Recommended citation: Naderalvojoud, B., Ucan, A., & Sezer, E. A. (2018, October). HUMIR at IEST-2018: Lexicon-Sensitive and Left-Right Context-Sensitive BiLSTM for Implicit Emotion Recognition. In Proceedings of the 9th Workshop on Computational Approaches to Subjectivity, Sentiment and Social Media Analysis (pp. 182-188).
 
