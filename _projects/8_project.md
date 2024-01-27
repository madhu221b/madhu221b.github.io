---
layout: page
title: Fairness in Link Prediction Through Active Learning
description: 
img: assets/img/al_process.png
importance: 1
category: Masters
---


 Social media has become a prominent carrier of media and information. A major downside of these platforms is that they are suspected of creating "echo-chambers" due to their people recommender systems. The echo chambers lead to the amplification of extreme ideological opinions among like-minded individuals while marginalizing minor communities. We use active learning to steer the link recommender algorithm (Node2Vec) to generate link predictions in a way that minorities are well-represented within the community. We design active learning loop intending to improve the ability of minority nodes to become major information carriers. To assess the fairness towards minority nodes due to active learning we introduce two metrics to evaluate how important minority nodes become over time and how much they disperse within local communities to improve their representation. We find that in a strong
majority homophilic network, active learning successfully intervenes to improve the representation of minority nodes. However, in a strongly minority homophilic network, active learning relies on minority node-size intervention to increase fairness towards minority nodes.

The code implementation of the study is publicly available [here](https://github.com/madhu221b/himl-link-prediction).

The report is [here](https://github.com/madhu221b/himl-link-prediction/blob/main/report.pdf).