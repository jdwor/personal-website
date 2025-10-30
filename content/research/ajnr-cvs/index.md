---
author: Jordan D. Dworkin, Pascal Sati, Andrew Solomon, Dzung L. Pham, Richard Watts, Melissa L. Martin, Daniel Ontaneda, Matthew K. Schindler, Daniel S. Reich & Russell T. Shinohara
categories:
date: "2018-10-08"
slug: ajnr-cvs
draft: false
excerpt: <span style="font-size:.9em">{*American Journal of Neuroradiology*, 2018}</span>
layout: single
links:
- icon: doi
  icon_pack: ai
  name: paper
  url: http://www.ajnr.org/content/39/10/1806
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/PennSIVE/lesiontools/blob/master/R/centralveins.R
title: Automated integration of multimodal MRI for the probabilistic detection of the central vein sign in MS lesions
---

## Abstract

The central vein sign is a promising MR imaging diagnostic biomarker for multiple sclerosis. Recent studies have demonstrated that patients with MS have higher proportions of white matter lesions with the central vein sign compared with those with diseases that mimic MS on MR imaging. However, the clinical application of the central vein sign as a biomarker is limited by interrater differences in the adjudication of the central vein sign as well as the time burden required for the determination of the central vein sign for each lesion in a patient's full MR imaging scan. In this study, we present an automated technique for the detection of the central vein sign in white matter lesions. Using multimodal MR imaging, the proposed method derives a central vein sign probability, πij, for each lesion, as well as a patient-level central vein sign biomarker, ψi. The method is probabilistic in nature, allows site-specific lesion segmentation methods, and is potentially robust to intersite variability. The proposed algorithm was tested on imaging acquired at the University of Vermont in 16 participants who have MS and 15 participants who do not. By means of the proposed automated technique, participants with MS were found to have significantly higher values of ψ than those without MS (ψ̅MS = 0.55 ± 0.18; ψ̅non-MS = 0.31 ± 0.12; P < .001). The algorithm was also found to show strong discriminative ability between patients with and without MS, with an area under the curve of 0.88. The current study presents the first fully automated method for detecting the central vein sign in white matter lesions and demonstrates promising performance in a sample of patients with and without MS.