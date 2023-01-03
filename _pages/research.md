---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

Research Topics
------
**Topic I: Dissemination of Multimodal Information in Directed Graph**

<img src='/images/r3.png' width='280'>

This research aims at proposing a data-driven yet interpretable framework towards modeling multimoadl information propagation in directed graphs. Applications of this research include vehicular network, social network, and other network scenarios etc. 





**Topic II: Trust Modeling in Online Social Networks (OSNs)**

<img src='/images/r1.png' width='480'>


This research contains a series of approaches for modeling trust relations in online social networks (OSNs) accurately, efficiently and practically. Applications of this research include online disinformation analysis, troll account detection, and precision marketing, etc.  

An important component of this research is based upon a deductive model called Three-Valued Subjective Logic (3VSL). This component aims at accurately
predicting the trust relation between any pair of indirectly connected nodes in arbitrary social network topology. Therefore, 3VSL can handle complex network topology as well as conduct accurate prediction in trust social networks.

Another component is an algorithmic framework for an equivalent implementation of 3VSL, but can be efficiently executed. This componebt enables massive implement of the 3VSL model in large-scale social networks. 

The last but never the least component is a neural network-based solution, which aims at build the trust model in a data-driven manner. Derived from 3VSL, We employs a neural network (NN) to reconstruct the logic operations in 3VSL. The parameters of the NN can be learned by treating original trust relations in a TSN as labeled samples. This component will finalized the trust model as a practical and effective solution for trust assessment in social networks. 

**Topic III: Social Media Opinion Analysis**

<img src='/images/r2.png' width='500'>

In this research, we employ NLP and machine learning approaches to develop a series of opinion analysis systems that provide business insights from text data in an automatic, timely and explainable manner. This research encompasses my work at Stratifyd, Inc. 

One of the systems is a theme summarization module for automatic public opinion briefing without label information. The model aims at categorizing and summarizing the frequently mentioned opinions from social media, e-commerce and contact center data in an unsupervised manner and visualize them in a read-friendly format. On top of the summarization module, an opinion trend detection module is further implemented to monitor the emerging topics via modeling the semantic distribution change in temporal domain. 

Another essential system is a weakly supervised multi-label text classification module for opinion categorization with very limited label information. It  aims at timely categorizing public opinions based upon users’ time-changing interests with the least manual effort in data labeling. 

In addition, we also developed an editable neural sentiment module for sentiment analysis. With this module, users can understand the logic behind the sentiment score and edit the prediction results based upon their own business logic, without retraining the model like traditional neural sentiment model. This model aims at providing users the accuracy of an neural network-based model, as well as flexibility and transparency of a lexicon-based sentiment model. 

Other projects I have successfully delivered under this topic include a generic text classification training pipeline and a streaming/batch speech-to-text engine. The former one enables various text classification tasks in one solution, with add-on inference speedup options e.g., model compression and distillation, etc. The later one enables call center speech data transcription, including speech-to-text, speaker dierization and speech activity detection models. 

All of the work above, which plays an essential role at Stratifyd’s data analytic platform, is being applied upon more than 11 million
text/audio records per day.






