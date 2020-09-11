---
layout: project
title: Schools are not islands; we must mitigate community transmission to reopen schools
---
<!-- <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> -->

**Abstract.**


Throughout US states and much of the rest of the world school closures were implemented in March and April of 2020 in efforts to stave off the COVID-19 pandemic. In-person schooling has been thought to present a significant risk of infection to students, teachers, and the broader community. Remote learning however is not without its costs. In-person learning helps support the emotional and social development of young children. Reports are now indicating that the youngest learners and their families are finding remote learning particularly difficult. Schools often provide more than just a place to learn and are frequently sources of support for families providing much needed nutrition.

We use <a href="https://github.com/institutefordiseasemodeling/covasim">Covasim model</a>, a detailed agent based model of COVID-19 to evaluate the tradeoffs of different proposed strategies for reopening schools and identify the requirements to avoid significant community transmission. We explored 7 school reopening strategies including the use of face masks, physical distancing, cohorting students into distinct classrooms, screening, testing, and contact tracing, as well as changes to student schedules to reduce the number in school at the same time. Our work shows that phased school reopening starting with elementary schools, A/B day scheduling, and classroom cohorting presents the lowest risk strategy to include in-person learning.


This work also uses <a href="https://github.com/InstituteforDiseaseModeling/synthpops">SynthPops</a>, our open-source data-driven generative model of multilayer contact networks, to model detailed school network structures of contact between students, teachers, and additional school staff. We use census and municipal records to model realistic contact networks in different physical contact settings. For our latest schools work, we updated the model to generate more detailed classroom networks under different cohorting strategies.


<!--  **Read the latest reports [(1)]({{"https://covid.idmod.org/data/Schools_are_not_islands_we_must_mitigate_community_transmission_to_reopen_schools.pdf" | prepend: site.baseurl }}), [(2)]({{"https://covid.idmod.org/data/Maximizing_education_while_minimizing_COVID_risk.pdf" | prepend: site.baseurl }}).** -->

 **Read the latest [paper]({{"https://www.medrxiv.org/content/10.1101/2020.09.08.20190942v1" | prepend: site.baseurl }}).**

<!-- **Fig 3. Efficiency frontier describing the trade-off between COVID-19 attack rate and in-person school days lost for four community and workplace mobility scenarios. For a given level of mobility (dashed lines), points to the lower left are preferable, as they represent both a lower COVID-19 attack rate and fewer school days lost. The COVID attack rate is calculated as the number of new infections in the population over the first three months of the school term divided by the population of King County.**  -->
<br>
<figure class="image">
  <img src="/assets/projects/2020_schools_1/fig1.png" style="width: 100%"/>

  <caption>Fig 1. A schematic diagram of the in-person school contact networks of students,
  teachers and additional school staff under different cohorting strategies. Normal, 
  preCOVID-19 patterns allow for mixing of students and teachers across grades and classrooms.
  A cohorted strategy places elementary and middle school students into classrooms with
  their own teachers, preventing contact between students in different classrooms in these
  schools. High schools remain mixed due to the highly individualized schedules of students
  in many U.S. based high schools, including those in King County, Washington. Teachers
  and additional school staff have contacts with each other to reflect their use of common
  staff paces such as a teachers’ lounge, front office, and other rooms for preparation.</caption>
<br>


<br>
<figure class="image">
  <img src="/assets/projects/2020_schools_1/fig3.png" style="width: 100%"/>
  <caption>Fig 3. Efficiency frontier describing the trade-off between COVID-19 attack rate and in-person school days lost for four community and workplace mobility scenarios. For a given level of mobility (dashed lines), points to the lower left are preferable, as they represent both a lower COVID-19 attack rate and fewer school days lost. The COVID attack rate is calculated as the number of new infections in the population over the first three months of the school term divided by the population of King County.</caption>

<br>
