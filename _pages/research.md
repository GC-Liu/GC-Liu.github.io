---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

Past Projects
------

**Trust Modeling in Online Social Networks (OSNs)**

<img src='/images/r1.png' width='480'>


This project proposed a serious of approaches for modeling trust relations in online social networks (OSNs) accurately, efficiently and practically. 

The first component of this project is a deductive model called Three-Valued Subjective Logic (3VSL). 3VSL can accurately
predict the trust relation between any pair of indirectly connected nodes in arbitrary social network topology. Therefore, 3VSL can handle complex network topology as well as conduct accurate prediction in trust social networks.

The second component is an algorithm called OpinionWalk, which is an equivalent implementation of 3VSL, but can be efficiently executed. OpinionWalk enables massive implement of the 3VSL model in large-scale social networks. 

The third component is a neural network-based solution called NeuralWalk. Derived from 3VSL, NeuralWalk employs a neural network (NN) to reconstruct the logic operations in 3VSL. The parameters of the NN can be learned by treating original trust relations in a TSN as labeled samples. NeuralWalk finalized 3VSL as a practical and effective solution for trust assessment in social networks. 









{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}
