---
layout: page
title: Hitting "Probe"rty with Non-Linearity
description: We reformulate the design of non-linear structural probes making its design simpler yet effective. We also design a visualization framework that lets us qualitatively assess how strongly two words in a sentence are connected in the predicted dependency tree. 
img: assets/img/probing.jpg
importance: 3
category: Masters
---

Structural probes learn a linear transformation to find how dependency trees are embedded in the hidden states of language models. This simple design may not allow for full exploitation of the structure of the encoded information. Hence, to investigate the structure of the encoded information to its full extent, we incorporate non-linear structural probes. We reformulate the design of non-linear structural probes introduced by [(White
et al., 2021)](https://aclanthology.org/2021.naacl-main.12.pdf) making its design simpler yet effective. We also design a visualization framework that lets us qualitatively assess how strongly two words in a sentence are connected in the predicted dependency tree. We use this technique to understand which non-linear probe variant is good at encoding syntactical information. Additionally, we also use it to qualitatively investigate the structure of dependency trees that BERT encodes in each of its layers. We find that the radial basis function (RBF) is an effective non-linear probe for the BERT model than the linear probe.

For an in-depth understanding of our project, please refer to our paper [here](https://github.com/madhu221b/probing-lms/blob/master/report.pdf).

The code of this project can be found [here](https://github.com/madhu221b/probing-lms).

