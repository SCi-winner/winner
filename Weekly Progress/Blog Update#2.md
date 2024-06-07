# Blog Update-2: Final Resutls

## Overview
&emsp;&emsp;This is the poster of our project：

![Picture](https://github.com/SCi-winner/SCI.github.io/blob/main/img/Final.png)

## Conclusions
&emsp;&emsp;This is the final results of our project:
### 1 Lifting & Diving Device
The conclusion of the simulation results are as follow: 
1) Based on Newton's second law and fluid force equation, the diving process model is simplified. By comprehensively calculating gravity, pressure, viscous resistance of water, and force caused by water's adhesion mass, the corresponding dynamic and diving velocity images are obtained. In addition, the flow rate is calculated to be 15L per minute
2) By applying buoyancy regulation to unmanned buoyancy platform, two different buoyancy regulation methods are proposed.
3) Using ANSYS fluent software for fluid dynamics simulation, convergence results were obtained, which further proved the accuracy of the calculated data.
### 2 Monitoring Device
The yaw axis pan-tilt design uses Solidworks for static stress analysis and simulation, ensuring rationality by selecting materials via quality checks and finite element analysis. For ship identification, the advanced Yolov5 algorithm is implemented on a microcomputer for real-time, remote autonomous identification on floating platforms. Integrating ASFF and BiFPN into Yolov5 enhances detection capabilities. Dataset training and validation, prove its efficacy in ship detection through loss value comparisons.
Future considerations include:
1.Combining lidar for improved recognition accuracy, expanding recognition range from surface to underwater.
2.Adding a remote control module for data transmission to a control center via networks, with a custom app for simultaneous device monitoring.
3.Advancing to multi-axis pan-tilts with gyroscopic sensors for increased stability in rough seas.
### 3 Sun-tracking Solar Panel
In summary, the project successfully crafted a cutting-edge solar energy system for marine platforms using an STM32 microcontroller, marking significant strides in renewable energy use offshore and smart control systems. Key accomplishments include:
1. Boosted Efficiency: Advanced tracking, managed by the STM32, and a custom MATLAB EMS app optimized energy capture and system performance.
2. Structural Advancements: Lightweight yet sturdy ABS structures, 3D printed, and topology-optimized with tools like ABAQUS, ensuring maritime suitability.
3. Proven Field Durability: Real-world sea trials validated high performance and resilience, even in adverse weather, affirming design effectiveness.
4. Sustainability & Cost Benefits: Aligns with green initiatives, reduces carbon emissions, and offers cost-efficient self-powering, suited for oceanic ventures like monitoring and research.
Future directions involve exploring AI for enhanced energy management, and advanced materials to withstand harsher marine settings, thereby future-proofing the unmanned floating platform for broader global deployment.
### 4 Multifunctional Sensors
Overall, simulation outcomes indicate that wind speed exerts the dominant influence on sea state fluctuations. Image curve analyses demonstrate that altering wind speed dramatically modifies the wave energy of the sea surface, thereby significantly escalating the loading forces on surface platforms. While increasing wave frequency also marginally raises wave energy within a confined range, visual evidence suggests its impact is subordinate in sea state transformation.
Preliminary simulation designs employed modest parameters, yielding simplistic datasets insufficient for precise depiction of sea state variability and severity levels. Consequently, in subsequent enhancement phases, the plan incorporates additional sea surface parameters, such as real-time temperature, ocean currents, and typhoon effects, to enhance the platform's sea state assessment and forecasting capabilities. This integration aims to facilitate emergency avoidance maneuvers in challenging marine environments, thereby informing and refining the surface platform's design.
### 5 Structural Optimization
This part establishes a combined optimization framework for lightweight design of marine unmanned buoyancy platform structures, centered on the variable density method utilizing ABAQUS®'s Finite Element (FE) solver. It introduces improved strategies and algorithms to overcome initial inconsistencies, validating the framework's efficacy through numerical examples. Key findings include:
1.A topology optimization framework integrating MATLAB-ABAQUS for large-scale element handling, demonstrating practical engineering applicability.
2.An enhanced RNN-KD trees search strategy that significantly accelerates filtering processes, particularly beneficial for high-element counts.
3.Adoption of an innovative post-processing method combining MT and MTRI to refine optimized structures and adhere to volume constraints.
4.Successful optimization of diverse platform structures under varied conditions, highlighting broad engineering application potential.
Future advancements entail:
1.Incorporating multi-scale optimization of lattice materials, pivotal for integrating lattice structures with solid components to boost structural performance.
2.Enhancing algorithm efficiency within the framework to accommodate increasingly complex structures and larger meshes, capitalizing on ABAQUS®'s mesh-handling capacity.
