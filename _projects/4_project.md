---
layout: page
title: Re-Label-Free-XAI
description: This project includes code for implementations, experiments and supplementary studies used for reproducing the work and the experiments of the work ICML 2022 paper- 'Label-Free Explainability for Unsupervised Models' by Jonathan Crabbé and Mihaela van der Schaar.
img: assets/img/re_xai.png
importance: 3
category: Masters
related_publications: mainpaper
---

Deep learning models are getting more and more advanced,  making it difficult for humans to understand and retrace how an algorithm arrives at a specific result. To solve this problem, explanation methods were developed.

Post-Hoc methods separate explanations from models allowing explanation methods to be compatible with a variety of models. They treat these models as "black boxes" due to their increasing complexity. Most of the post-hoc explanation techniques require labels to explain black-box outputs and thus they work only in a supervised setting.


The paper *Label-Free Explainability for Unsupervised Models*, by J. Crabbé and M. van der Schaar 's goal is to explain black-box outputs in a label-free setting. The authors introduce two extensions for the __Feature Importance__ and the __Example Importance__ that highlight influential features and training examples respectively for a black box to construct representations at inference time. 


The contribution of our work is summarized as follows: 
<ol>
    <li>We reproduce the main experiments by Crabbé and Schaar to reproduce their main claims.</li>
    <li>We conduct additional experiments to assess the robustness of label-free techniques proposed by the authors. Since they originally experiment on image and time-series datasets, we extend their techniques to find salient features and training samples for graphs and text datasets respectively. </li> 
    <li>We find that one of the authors' claims is model-specific when we introduce a penalty term to the loss function of those models.</li> 
</ol>


The code implementation of our study is publicly available [here](https://github.com/valentinosPariza/Re-Label-Free-XAI).

Our paper is soon to be published but till then you can read our submitted draft which is [here](https://github.com/madhu221b/Re-Label-Free-XAI/blob/main/MLRC_2022___FACT_AI__group_9_2023_cameraready.pdf).