---
title: "Generative design for COVID-19 and future pathogens using stochastic multi-agent simulation"
date: 2023-06-01
layout: projectSingle
draft: false

# Project thumb
category: [ "System", "Innovation" ]
image: "/projects/2023-OccSim/_[opt]teaser.jpg"
teaser: "/projects/2023-OccSim/_[opt]top.jpg"
metacontent: "We propose a generative design workflow that integrates a stochastic multi-agent simulation with the intent of helping building designers reduce the risk posed by COVID-19 and future pathogens."

# Meta-Data
conference: "Sustainable Cities and Society 2023"
con_date: "June 01"
keywords: "generative design / human-centered architecture / AI-driven"
researcher: "Bokyung Lee, Michael Lee, Jeremy Mogk, Rhys Goldstein, Jacky Bibliowicz, Frederik Brudy, Alexander Tessier."
summary: "• We propose a generative design workflow that integrates a stochastic multi-agent simulation with the intent of helping building designers reduce the risk posed by COVID-19 and future pathogens. Our custom simulation randomly generates activities and movements of individual occupants, tracking the amount of virus transmitted through air and surfaces from contagious to susceptible agents. The stochastic nature of the simulation requires that many repetitions be performed to achieve statistically reliable results. Accordingly, a series of initial experiments identified parameter values that balanced the trade-off between computational cost and accuracy. Applying generative design to a case study based on an existing office space reduced the predicted transmission by around 10% to 20% compared with a baseline set of layouts. Additionally, a qualitative examination of the generated layouts revealed design patterns that may reduce transmission. Stochastic multi-agent simulation is a computationally expensive yet plausible way to generate safer building designs."
tags: ["Design", "Bab", "Bibibib"]
shortkeys: "#generative design"

# description
description: "This is meta description"

# links
links:
  - label : "Paper"
    link : "https://www.dropbox.com/scl/fi/fddvnga6l8upa8hdatfcx/2023-sustainable.pdf?rlkey=2oa8d7tatl2eb459ov9tl8ihq&dl=0"
  - label : "Source URL"
    link : "https://www.sciencedirect.com/science/article/abs/pii/S221067072300272X"
  - label : "Project Page"
    link : "/projects/2023-occsim/"

---

<img src="../../projects/2023-OccSim/framework.jpg" width="50%"/>

The multi-agent-based virus transmission simulation model architecture (Lee et al., 2021). A schedule manager triggered both planned and unplanned activities for agents in the building. When triggered, a virus manager triggers virus transmission in the space based on the associated agents’ locations and activity type (e.g., cough, sneeze, touch).

<br>
<img src="../../projects/2023-OccSim/sim.jpg" width="50%"/>

Screen-captured images of our simulation when the graphical mode was activated. The images were captured at specific moments: when (a) 3600 s, (b) 7200 s, and (c) 10 800 s had passed since the simulation started. The grid heat map on the background visualizes the location-specific concentration of virus in the air (𝜓𝑐𝑒𝑙𝑙 ), with the range from 0 to 1. The susceptible agents are represented as blue, while the contagious agents are represented as red. (For interpretation of the references to colour in this figure legend, the reader is referred to the web version of this article.)

<br>
<img src="../../projects/2023-OccSim/plot.jpg" width="50%"/>

Simulation results from different percentages of contagious agents: 5%, 10%, 15%, 20%, 25%, 30%, using both a low (40 agents in total) and high capacity setting (100agents in total). Swarm plots (top) and violin plots (bottom) demonstrate the distribution of the results obtained from 400 simulation runs, for each combination of conditions.
Fig. 5.


<br>
<img src="../../projects/2023-OccSim/framework2.jpg" width="50%"/>

Scope and contribution of our work.


<br>
<img src="../../projects/2023-OccSim/generative1.jpg" width="50%"/>

Generative geometry model for case study (Nagy, Lau et al., 2017).


<br>
<img src="../../projects/2023-OccSim/generative2.jpg" width="50%"/>

Top ten performing designs from each trial in terms of air+surface, air, and surface metrics.


<br>
<img src="../../projects/2023-OccSim/generative3.jpg" width="50%"/>

Air and surface transmission metrics over generation number, demonstrating NSGA-II optimization’s ability to minimize virus transmission over successive generations.


<br>
<img src="../../projects/2023-OccSim/generative4.jpg" width="50%"/>

Top 10 highest and lowest performing designs for air mean from Trial A run.
