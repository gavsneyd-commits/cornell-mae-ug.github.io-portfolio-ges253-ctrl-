---
layout: project
title: Turbojet Engine Analysis
description: A project analyzing the thermodynamic principles and performance of turbojet engines, focusing on energy conversion and efficiency.
technologies: [MATLAB, SolidWorks, Google]
image: "/assets/images/Jet-engine.webp"
published: true
---

<img src="{{ "/assets/images/J85_ge_17a_turbojet_engine-scaled-1.jpg" | relative_url }}" alt="Cutaway of a J85 turbojet engine" style="max-width:60%; height:auto;" />

## Project: Turbojet Engine Analysis

This project focuses on understanding and modeling the operation of a turbojet engine as a thermodynamic device. The goal was to analyze the energy conversion processes involved, from air intake to exhaust, and evaluate the performance of the engine in terms of thrust and efficiency.

<img src="{{ "/assets/images/bd7dde29-0c55-4330-a15a-865d2dda9064.png" | relative_url }}" alt="Turbojet engine schematic and analysis workflow" style="max-width:60%; height:auto;" />

## Project Description

Turbojet engines are a class of air-breathing jet engines widely used in aviation. They operate by drawing in air, compressing it, mixing it with fuel, and igniting the mixture to produce high-velocity exhaust gases that generate thrust. The main challenge in turbojet design is maximizing thrust while maintaining fuel efficiency, which involves optimizing the compression ratio, turbine efficiency, and nozzle design. This project models these processes using idealized thermodynamic cycles and computational simulations.

![Turbojet engine cross-section diagram]({{ "/assets/images/800px-Jet_engine.svg.webp" | relative_url }})

## Approach

The project began with a literature review of turbojet operation and the Brayton cycle. A 1D computational model of the engine was created using MATLAB, incorporating components such as the compressor, combustion chamber, turbine, and nozzle. Key parameters, including air mass flow rate, combustion temperature, and pressure ratios, were varied to evaluate their effect on thrust and thermal efficiency. Flow diagrams and thermodynamic state plots were generated to visualize energy conversion across the engine components. SolidWorks was used to design simplified schematics of the engine for illustration.

<img src="{{ "/assets/images/Turbjet_Press_temps.png" | relative_url }}" alt="Pressure, temperature and flow velocity through the engine stages" style="max-width:60%; height:auto;" />

## Results

Simulation results show that increasing the compressor pressure ratio improves thermal efficiency but also increases turbine inlet temperature, requiring careful material considerations. The maximum calculated thrust at optimal operating conditions was consistent with theoretical predictions for a small turbojet engine. Performance plots highlight the relationship between fuel consumption, air mass flow, and engine thrust, demonstrating the trade-offs inherent in turbojet design.

![Turbojet heat exchanger locations]({{ "/assets/images/HS-graphic-1024x610.jpg" | relative_url }})

## Potential Modification

One potential modification to improve turbojet engine performance is the addition of a **heat exchanger or intercooler** between the compressor and combustion chamber. In a standard turbojet, the air is compressed and then directly sent to the combustion chamber. However, compressing air increases its temperature, which reduces density and the overall efficiency of the subsequent combustion process. By cooling the compressed air before it enters the combustion chamber, an intercooler reduces its temperature, allowing more air mass to enter the chamber at the same pressure. This effectively increases the engine’s thrust potential without raising fuel consumption. Additionally, cooler air entering the combustion chamber reduces the maximum temperature the turbine sees, which can improve component life and allow the use of lighter or less heat-resistant materials. Overall, integrating an intercooler is a modification that enhances thermal efficiency, increases thrust, and improves the durability of the turbojet engine.

## Lessons Learned

Through this project, the importance of balancing compression, combustion, and turbine efficiency became clear. The project reinforced the role of thermodynamic analysis in engine design and showed how simulation tools can predict performance before physical prototyping. It also emphasized the impact of heat management and component materials on overall efficiency.

![Turbojet engine on display]({{ "/assets/images/Jet-engine.webp" | relative_url }})

### References

- Mattingly, J. D. *Elements of Propulsion: Gas Turbines and Rockets*. AIAA, 2006.  
- Hill, P. G., & Peterson, C. R. *Mechanics and Thermodynamics of Propulsion*. Pearson, 1992.  
- Turns, S. R. *An Introduction to Combustion: Concepts and Applications*. McGraw-Hill, 2012.  