---
title: "FairyTED: A Fair Rating Predictor for TED Talk Data"
collection: publications
permalink: /publication/paper2
excerpt: 'We use counterfactual fairness to create a fair rating predictor model for the public speaking dataset(TEDtalk).'
date: 2020-02-10
venue: 'AAAi 2020, AI for Social Impact'
paperurl: 'https://arxiv.org/abs/1911.11558'
---
We address the problem of predicting the quality of public speeches while being fair with respect to sensitive attributes of the speakers, e.g. gender and race. We use the TED talks as an input repository of public speeches because it consists of speakers from a diverse community and has a wide outreach. Utilizing the theories of Causal Models, Counterfactual Fairness and state-of-the-art neural language models, we propose a mathematical framework for fair prediction of the public speaking quality. We employ grounded assumptions to construct a causal model capturing how different attributes affect public speaking quality. This causal model contributes in generating counterfactual data to train a fair predictive model. Our framework is general enough to utilize any assumption within the causal model. Experimental results show that while prediction accuracy is comparable to recent work on this dataset, our predictions are counterfactually fair with respect to a novel metric when compared to true data labels. The FairyTED setup not only allows organizers to make informed and diverse selection of speakers from the unobserved counterfactual possibilities but it also ensures that viewers and new users are not influenced by unfair and unbalanced ratings from arbitrary visitors to the this http URL website when deciding to view a talk.

[[PDF]](https://arxiv.org/abs/1911.11558)
