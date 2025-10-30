---
author: Jason Roy, Kirsten J. Lum, Bret Zeldow, Jordan D. Dworkin, Vincent Lo Re, III & Michael J. Daniels
categories:
  - Statistical methods
date: "2018-03-26"
slug: bnp-caus
draft: false
excerpt: <span style="font-size:.9em">{*Biometrics*, 2018}</span>
layout: single
links:
- icon: doi
  icon_pack: ai
  name: paper
  url: https://onlinelibrary.wiley.com/doi/abs/10.1111/biom.12875
- icon: door-open
  icon_pack: fas
  name: preprint
  url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7568223/
title: Bayesian nonparametric generative models for causal inference with missing at random covariates
---

## Abstract

We propose a general Bayesian nonparametric (BNP) approach to causal inference in the point treatment setting. The joint distribution of the observed data (outcome, treatment, and confounders) is modeled using an enriched Dirichlet process. The combination of the observed data model and causal assumptions allows us to identify any type of causal effect—differences, ratios, or quantile effects, either marginally or for subpopulations of interest. The proposed BNP model is well-suited for causal inference problems, as it does not require parametric assumptions about the distribution of confounders and naturally leads to a computationally efficient Gibbs sampling algorithm. By flexibly modeling the joint distribution, we are also able to impute (via data augmentation) values for missing covariates within the algorithm under an assumption of ignorable missingness, obviating the need to create separate imputed data sets. This approach for imputing the missing covariates has the additional advantage of guaranteeing congeniality between the imputation model and the analysis model, and because we use a BNP approach, parametric models are avoided for imputation. The performance of the method is assessed using simulation studies. The method is applied to data from a cohort study of human immunodeficiency virus/hepatitis C virus co-infected patients.