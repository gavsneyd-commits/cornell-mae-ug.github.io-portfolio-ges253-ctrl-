---
layout: project
title: Thermodynamic Device Analysis
description: in-class heat exchanger mini-lab
technologies: []
image: /assets/images/setup.png
---


I chose to work with a given heat exchanger that we could analyze by tweaking variables. 

We have two reservoirs, one of hot water and one of cold water, with pumps connecting them to a heat exchanger designed to operate in counter-flow. The hot reservoir's temperature can be adjusted using the attached sous vide machine, while the cold reservoir is kept cool with ice and a cooler. The pump flow rates can be adjusted with a dial, and the heat exchanger can be set to flow in the same direction by swapping the positions of one of the reservoirs. 

![Heat exchanger setup]({{ "/assets/images/heat-exchanger.png" | relative_url }})

The change we decided to implement was a change in the starting temperature of the hot reservoir. One interesting thing to note about the results is that the cold reservoir actually ended up hotter than the hot reservoir, in both cases. We actually discovered that the we had accidentally left the pump in the cold reservoir on the slowest speed while the pump in the hot reservoir was on the highest speed, so a further experiment could be to swap the speeds to see if that changes anything, maybe even put the heat exchanger in parallel flow because we know counter flow is supposed to help with heat being exchanged.

![Control-Volume Thermodynamic Equations]({{ "/assets/images/equations.png" | relative_url }})

![Data]({{ "/assets/images/Data.png" | relative_url }})

![Rates-Calculated]({{ "/assets/images/Rates-calculated.png" | relative_url }})

