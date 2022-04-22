---
author: Jordan D. Dworkin
categories:
date: "2021-08-01"
slug: r-lqt
draft: false
excerpt: The lesion quantification toolkit (LQT) is a publicly available software package for quantifying the probabilistic impacts of focal brain lesions on structural connectivity.
layout: single
links:
- icon: github
  icon_pack: fab
  name: R package
  url: https://github.com/jdwor/LQT
title: Lesion quantification toolkit
---

## Description

LQT is an R implementation of the lesion quantification toolkit, based on the paper “Lesion Quantification Toolkit: A MATLAB software tool for estimating grey matter damage and white matter disconnections in patients with focal brain lesions” by Griffis et al. The LQT is a publicly available software package for quantifying the structural impacts of focal brain lesions. It uses atlas-based approaches to estimate parcel-level grey matter lesion loads and multiple measures of white matter disconnection severity that include tract-level disconnection measures, voxel-wise disconnection maps, and parcel-wise disconnection matrices. The toolkit also estimates lesion-induced increases in the lengths of the shortest structural paths between parcel pairs, which provide information about changes in higher-order structural network topology.

The R package creates data structures necessary for applying the methods directly to MNI-registered lesion maps from either a single patient or a full study. The package then allows the user to create figures for visualization and summary, and to compile analysis-ready datasets for research.