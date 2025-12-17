---
layout: project
title: Small Wind Turbine Blade Design
description: Final Class Project
technologies: [Autodesk Fusion, MATLAB, Wind Tunnel, LabView]
image: /assets/images/blade.jpg
---
## MAE 4272 – Fluids and Heat Transfer Laboratory, Cornell University
---
#### Project Overview

As part of MAE 4272, our team designed, fabricated, and tested blades for a small-scale horizontal-axis wind turbine. The objective was to maximize power extraction while satisfying geometric, material, and operational constraints imposed by a laboratory wind tunnel environment. Rather than optimizing performance at a single wind speed, the blade was designed for operation in a realistic wind environment described by a Weibull distribution, reflecting how turbines operate in practice. The project combined aerodynamic theory, numerical modeling, CAD design, and experimental testing.

#### Design Process

We developed the blade geometry using Blade Element Momentum (BEM) and Blade Element Theory (BET), implemented through a custom MATLAB code that generated chord and twist distributions along the blade span. Multiple cambered airfoils were evaluated under consistent assumptions, informed by prior lab results showing that cambered airfoils provide higher lift and torque at comparable operating conditions. Key design decisions included tapering the chord to reduce drag and inertial loading toward the blade tip, and introducing spanwise twist to maintain a near-constant angle of attack. Based on predicted power output, torque, and structural stress, the NACA 4412 airfoil was selected as the final design.

#### Testing and Results

The final three-blade rotor was manufactured and tested in the Bellis Lab wind tunnel across five fan frequencies corresponding to wind speeds that capture roughly 70% of the Weibull probability mass. Power and rotational speed were measured under increasing torque loads to generate Power vs. RPM curves. Because experimental limitations prevented collecting data at all RPMs for every wind speed, third-order polynomial fits constrained through the origin were used to interpolate performance at a constant operating speed. The resulting Power vs. Velocity trend showed increasing power with wind speed, consistent with theoretical expectations, and demonstrated that the blade performed near its intended design condition.

![Power vs Rotation Rate]({{ "/assets/images/pr-graph.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Power vs Velocity]({{ "/assets/images/pv-graph.jpg" | relative_url }}){: .inline-image-l}

####  My Contribution

I focused on the CAD and data analysis portions of the project. This included creating the final blade geometryu, comparing candidate airfoil geometries, post-processing wind tunnel data, and generating the interpolated Power vs. Velocity results used for final performance evaluation. I also contributed to interpreting experimental limitations and connecting test results back to the design assumptions.



