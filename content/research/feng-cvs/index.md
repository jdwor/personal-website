---
author: Fengling Hu, Zheng Ren, Luyun Chen, Alessandra M. Valcarcel, Jordan Dworkin, Brian Renner, Lynn Daboul, Carly M. O’Donnell, Elizabeth D. Verter, Abigail R. Manning, Kelly A. Clark, Eunchan Bae, Christina Chen, Carolyn Lou, Theodore D. Satterthwaite, Haochang Shou, Michel Bilello, Kunio Nakamura, Amit Bar-Or, Peter A. Calabresi, Leorah Freeman, Roland G. Henry, Erin E. Longbrake, Jiwon Oh, Matthew K. Schindler, Martina Absinta, Andrew J. Solomon, Nancy L. Sicotte, Daniel Ontaneda, Daniel S. Reich, Pascal Sati, & Russell T. Shinohara
categories:
  - Neuroimaging methods
date: "2025-10-10"
slug: feng-cvs
draft: false
excerpt: <span style="font-size:.9em">{*Imaging Neuroscience*, 2025}</span>
layout: single
links:
- icon: doi
  icon_pack: ai
  name: paper
  url: https://direct.mit.edu/imag/article/doi/10.1162/IMAG.a.932/133343/Automated-segmentation-of-multiple-sclerosis
title: Automated segmentation of multiple sclerosis lesions, paramagnetic rims, and central vein sign on MRI provides reliable diagnostic biomarkers 
---

## Abstract

Multiple sclerosis (MS) is characterized by central nervous system lesions detectable via MRI. Existing diagnostic criteria incorporate presence of white matter lesions, but specificity can be improved using MS-specific imaging biomarkers, including paramagnetic rim lesions (PRLs) and central vein sign (CVS). However, manual segmentation of lesions, PRLs, and CVS is time-consuming and subjective. We propose a fully-automated joint segmentation method called Automated Lesion, PRL, and CVS Analysis (ALPaCA). We trained ALPaCA using subject-level cross-validation on 47 adults with MS and 50 adults with radiological MS mimics. ALPaCA uses a voxel-wise lesion segmentation method to propose a large set of lesion candidates. Lesion candidates are input into a multi-contrast, multi-label 3D convolutional neural network as 3D patches to produce lesion, PRL, and CVS predictions. When multiple lesions exist within a patch, an attention mechanism identifies which lesion candidate to classify. At the lesion level, ALPaCA achieves cross-validation areas under the receiver operating characteristic curve (AUROCs) of 0.95, 0.91, and 0.87 for lesion, PRL, and CVS classification, outperforming previous methods (all p < 0.001). Correlations between subject-level ALPaCA lesion and PRL scores with manual counts are higher than those of previous methods (p < 0.001; p = 0.03). Subject-level ALPaCA PRL and CVS scores are highly associated with MS in logistic regressions, when controlling for age and sex (p < 0.001). ALPaCA allows for fully-automated simultaneous segmentation of MS lesions, PRLs, and CVS using clinically-feasible scans. These segmentations outperform existing methods at the lesion and subject level.