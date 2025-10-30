---
author: Danni Tu, Manu S. Goyal, Jordan D. Dworkin, Samuel Kampondeni, Lorenna Vidal, Eric Biondo-Savin, Sandeep Juvvadi, Prashant Raghavan, Jennifer Nicholas, Karen Chetcuti, Kelly Clark, Timothy Robert-Fitzgerald, Theodore D. Satterthwaite, Paul Yushkevich, Christos Davatzikos, Guray Erus, Nicholas J. Tustison, Douglas G. Postels, Terrie E. Taylor, Dylan S. Small, & Russell T. Shinohara
categories:
date: "2023-09-01"
slug: biom-lowfield
draft: false
excerpt: <span style="font-size:.9em">{*Biometrics*, 2023}</span>
layout: single
links:
- icon: doi
  icon_pack: ai
  name: paper
  url: https://academic.oup.com/biometrics/article-abstract/79/3/2417/7513879
- icon: door-open
  icon_pack: fas
  name: preprint
  url: https://www.biorxiv.org/content/10.1101/2020.12.23.424020v3
title: Automated analysis of low-field brain MRI in cerebral malaria
---

## Abstract

A central challenge of medical imaging studies is to extract biomarkers that characterize disease pathology or outcomes. Modern automated approaches have found tremendous success in high-resolution, high-quality magnetic resonance images. These methods, however, may not translate to low-resolution images acquired on magnetic resonance imaging (MRI) scanners with lower magnetic field strength. In low-resource settings where low-field scanners are more common and there is a shortage of radiologists to manually interpret MRI scans, it is critical to develop automated methods that can augment or replace manual interpretation, while accommodating reduced image quality. We present a fully automated framework for translating radiological diagnostic criteria into image-based biomarkers, inspired by a project in which children with cerebral malaria (CM) were imaged using low-field 0.35 Tesla MRI. We integrate multiatlas label fusion, which leverages high-resolution images from another sample as prior spatial information, with parametric Gaussian hidden Markov models based on image intensities, to create a robust method for determining ventricular cerebrospinal fluid volume. We also propose normalized image intensity and texture measurements to determine the loss of gray-to-white matter tissue differentiation and sulcal effacement. These integrated biomarkers have excellent classification performance for determining severe brain swelling due to CM.