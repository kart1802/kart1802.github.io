---
title: Simulation of Soft Robot Hand
date: 2022-09-30
images:
- /images/SW_Design.png
description: A study and experiment of a soft robot hand in SOFA
---

This was one of my personal projects that I worked on in Summer 2022.

Not limiting my work to rigid body systems, I became particularly interested in the topic of Soft Robot Simulation. All traditionally used Physics engines and simulators have optimized their working for rigid body systems. Soft Robots bring in the problem of nonlinear characteristics and infinite DOF, hence making them difficult to compute. Hence, many data-driven approaches are extensively researched upon. Simulation software like SOFA makes it easy to work and their solvers do the work showing close to realistic behaviours.
    
In this project, the prototypes of the fingers were designed in SolidWorks and the FEM analysis of these structures were carried out.
    
The structures having multiple chambers and smooth, curved body were showcasing greater deflection. Based on the higher bending angle on application of same amount of pressure, Prototype 4 was chosen for the simulation purpose. 
    
The structure was meshed and exported for simulation
    
After importing in SOFA, various material properties, solvers, and constraints were defined and satisfactory motion of fingers were recorded

To check out the documentation of the work till now, click [here](https://drive.google.com/file/d/1cRkN751rlhMFbgSfjBxvMoK9e-g_HvJ6/view?usp=sharing)
