---
author: Jordan D. Dworkin
categories:
date: "2018-09-15"
slug: net-scape
draft: false
excerpt: An analysis of the NeuroImage's keyword trends and networks over the past 10 years. Illustrates changing popularity of various topics in the field, and provides an interactive user interface.
layout: single
links:
- icon: open-data
  icon_pack: ai
  name: RShiny dashboard
  url: https://jdwor.shinyapps.io/NeuroimagingLandscape/
title: The landscape of neuroimaging research
---

## Description

As the field of neuroimaging grows, it can be difficult for scientists within the field to gain and maintain a detailed understanding of its ever-changing landscape. While collaboration and citation networks highlight important contributions within the field, the roles of and relations among specific areas of study can remain quite opaque. Here, I applied techniques from network science to map the landscape of neuroimaging research documented in the journal NeuroImage over the past decade. I created a network in which nodes represent research topics, and edges give the degree to which these topics tend to be covered in tandem. This dashboard gives users the ability to explore the structure of this network; it allows for visualization of topic co-occurrence and prevalence over time, as well as node-level graph theoretic metrics.