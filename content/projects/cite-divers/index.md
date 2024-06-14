---
author: Jordan D. Dworkin, Perry Zurn, Dani S. Bassett, and the Complex Systems Lab
categories:
date: "2020-05-01"
slug: cite-divers
draft: false
excerpt: Reference lists show marked gender and racial/ethnic imbalances. To mitigate these disparities, we discuss ethical considerations and offer practical recommendations and tools for scientists
layout: single
links:
- icon: obp
  icon_pack: ai
  name: Commentary
  url: https://www.cell.com/neuron/fulltext/S0896-6273(20)30357-3
- icon: github
  icon_pack: fab
  name: Python binder
  url: https://github.com/dalejn/cleanBib
title: Citation tools and initiatives
---

## Description

LQT is an R implementation of the lesion quantification toolkit, based on the paper “Lesion Quantification Toolkit: A MATLAB software tool for estimating grey matter damage and white matter disconnections in patients with focal brain lesions” by Griffis et al. The LQT is a publicly available software package for quantifying the structural impacts of focal brain lesions. It uses atlas-based approaches to estimate parcel-level grey matter lesion loads and multiple measures of white matter disconnection severity that include tract-level disconnection measures, voxel-wise disconnection maps, and parcel-wise disconnection matrices. The toolkit also estimates lesion-induced increases in the lengths of the shortest structural paths between parcel pairs, which provide information about changes in higher-order structural network topology.

The R package creates data structures necessary for applying the methods directly to MNI-registered lesion maps from either a single patient or a full study. The package then allows the user to create figures for visualization and summary, and to compile analysis-ready datasets for research.