---
layout: project
title: Generating Synthetic Populations Using Census and Survey Data
---
<!-- <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> -->

**Abstract.**

SynthPops is an <a href="https://github.com/InstituteforDiseaseModeling/synthpops">open-source</a> generative and data-driven model designed to provide the wider modeling community with tools to generate multilayer networks in diverse populations around the world. The model generates realistic contact networks reflecting age mixing patterns inferred for 3 important settings of physical contact: households, schools, and workplaces.

SynthPops is currently being used to inform agent-based models of transmission and non-pharmaceutical interventions (NPI), most notably in King County, WA. The model produces multilayer contact networks of physical interaction and has helped to estimate transmission rates in the region under current shelter in place orders and to forecast the needed scale of NPI efforts to safely move out of these orders, as well as the tradeoffs of different school reopening strategies. The model has already been extended to look at another important layer of contact: long term care facilities in the Seattle area. This layer includes both residents living at these care facilities and staff members working there, but living in non-facility homes and interacting with other community members. The model connects residents and staff members to each other and identifies the status of each so that we can design detailed interventions that reflect policies adopted by these facilities (the restriction of most resident contact with staff members only) to reduce the risk of transmission to residents who represent a particularly vulnerable population to COVID.

Beyond western settings, SynthPops is currently being extended in detail to model social contact patterns in Dakar, Senegal to help in modeling the student based health information program <a href="http://www.etudiantscontrec19.sn/">Sénégal : Programme Cent Mille Étudiants Contre le COVID-19</a>.


 **Read the latest King County works: [(1)]({{"https://www.medrxiv.org/content/10.1101/2020.07.15.20154765v3" | prepend: site.baseurl }}), [(2)]({{"https://www.medrxiv.org/content/10.1101/2020.07.15.20154765v3" | prepend: site.baseurl }}).**


 **Check out the [project]({{"https://github.com/institutefordiseasemodeling/synthpops/" | prepend: site.baseurl }}) in development.**

**Schematic representation of the workflow for modeling human mixing patterns and infection transmission dynamics.** 
<br>
<figure class="image">
  <img src="/assets/projects/2020_synthpops/si_fig_4.svg" style="width: 100%"/>

<br>
<!-- <object data="/assets/projects/2020_synthpops/si_fig_4.svg" type="image/svg+xml"></object>
 -->
<!-- **Short video describing the work. Recorded for KDD'17.** <br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yiKJCgLE4" frameborder="0" allowfullscreen></iframe>
 -->

