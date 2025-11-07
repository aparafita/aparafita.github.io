---
title: "Estimand-Agnostic Causal Query Estimation With Deep Causal Graphs"
collection: publications
category: manuscripts
permalink: /publication/2022-07-04-estimand-agnostic
excerpt: "Causal Queries are usually estimated by means of an estimand, a formula consisting of observational terms that can be computed using passive data. Each query results in a different formula, which makes estimand-based methods extremely ad-hoc. In this work, we propose an estimand-agnostic framework capable of computing any identifiable causal query on an arbitrary Causal Graph (even in the presence of latent confounders) with only one general model. We provide multiple implementations of this general framework that leverage the expressive power of Neural Networks and Normalizing Flows to model complex distributions, and we derive estimation procedures for all kinds of observational, interventional and counterfactual queries, valid for any kind of graph for which the query is identifiable. Finally, we test our techniques in a modelling setting and an estimation benchmark to show how, despite being a query-agnostic framework, it can compete with query-specific models. Our proposal includes an open-source library that allows easy application and extension of our techniques for researchers and practitioners alike."
date: 2022-07-04
venue: 'IEEE Xplore'
# slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9815055'
citation: "Parafita, A., & Vitria, J. (2022). Estimand-agnostic causal query estimation with deep causal graphs. IEEE Access, 10, 71370-71386."
---

**Abstract**: Causal Queries are usually estimated by means of an estimand, a formula consisting of observational terms that can be computed using passive data. Each query results in a different formula, which makes estimand-based methods extremely ad-hoc. In this work, we propose an estimand-agnostic framework capable of computing any identifiable causal query on an arbitrary Causal Graph (even in the presence of latent confounders) with only one general model. We provide multiple implementations of this general framework that leverage the expressive power of Neural Networks and Normalizing Flows to model complex distributions, and we derive estimation procedures for all kinds of observational, interventional and counterfactual queries, valid for any kind of graph for which the query is identifiable. Finally, we test our techniques in a modelling setting and an estimation benchmark to show how, despite being a query-agnostic framework, it can compete with query-specific models. Our proposal includes an open-source library that allows easy application and extension of our techniques for researchers and practitioners alike.
