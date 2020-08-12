---
layout: project
title: Controlling COVID-19 via test-trace-quarantine
---
<!-- <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> -->

**Abstract.**


COVID-19 containment efforts in the United States so far have largely focused on physical distancing, including school and workplace closures. However, these interventions have come at an enormous societal and economic cost. Here, we use an agent-based model, calibrated to detailed demographic, mobility, and epidemiological data for the Seattle region, to investigate the feasibility of alternative control strategies, focusing on "test-trace-quarantine": a combination of (a) routine testing of primarily symptomatic individuals, (b) tracing and testing their known contacts, and (c) placing their contacts in quarantine. We assess the requirements for implementing this strategy, including its robustness to low compliance, delays, and other factors such as variability in overall transmission rates. We find that for the Seattle setting, if mask compliance remains high and schools remain closed, realistic levels of testing and tracing are sufficient to maintain epidemic control under a return to full workplace and community mobility. 

This work uses <a href="https://github.com/institutefordiseasemodeling/covasim">Covasim model</a>, a detailed agent based model of COVID-19, and <a href="https://github.com/InstituteforDiseaseModeling/synthpops">SynthPops</a>, an open-source data-driven generative model of multilayer contact networks. 

 **Read the latest [paper]({{"https://www.medrxiv.org/content/10.1101/2020.07.15.20154765v3" | prepend: site.baseurl }}).**

**Fig. 2. Modeled transmission dynamics. A: Infections over time by contact layer. B–C: Overdispersion of infections, with roughly equal numbers of infections attributable to individuals who transmit to 1–2 others, 3–5 others, or more than 5 others, with fewer than 10% of primary infections responsible for more than 50% of transmissions. D: Infections as a function of symptom onset, showing that slightly over half of infections are transmitted by symptomatic individuals.** 
<br>
<figure class="image">
  <img src="/assets/projects/2020_covid-19_ttq/fig2.png" style="width: 100%"/>

<br>

<!-- **Short video describing the work. Recorded for KDD'17.** <br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yiKJCgLE4" frameborder="0" allowfullscreen></iframe>
 -->

