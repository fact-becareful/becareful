---
title: Sycophancy in Language Model

description: |
  Accounting for Sycophancy in Language Model Uncertainty Estimation
people:
  - AS
  - MI
  - MA

layout: project
last-updated: 2024-10-17
---



## 

Effective human-machine collaboration requires machine learning models to externalize uncertainty, so users can reflect and intervene when necessary. For language models, these representations of uncertainty may be impacted by sycophancy bias: proclivity to agree with users, even if they are wrong. For instance, models may be over-confident in (incorrect) problem solutions suggested by a user. We study the relationship between sycophancy and uncertainty estimation for the first time. We propose a generalization of the definition of sycophancy bias to measure downstream impacts on uncertainty estimation, and also propose a new algorithm (SyRoUP) to account for sycophancy in the uncertainty estimation process. Unlike previous works on sycophancy, we study a broad array of user behaviors, varying both correctness and confidence of user suggestions to see how model answers (and their certainty) change. Our experiments across conversation forecasting and question-answering tasks show that user confidence plays a critical role in modulating the effects of sycophancy, and that SyRoUP can better predict these effects. From these results, we argue that externalizing both model and user uncertainty can help to mitigate the impacts of sycophancy bias.
