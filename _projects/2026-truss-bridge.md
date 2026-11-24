---
layout: project
title: Truss Bridge
description: Truss design for a pedestrian bridge across Ithaca gorge.
technologies:
  - Autodesk Fusion
featured: false
image: /portfolio/assets/images/final.png
imagealt: Final truss bridge design
---

![Bridge brainstorming](/portfolio/assets/images/brainstorm.png)

Started by looking into and sketching different bridge designs before settling on a Warren bridge, as it was widely considered one of the better simple truss designs.

![Overall free body diagram](/portfolio/assets/images/overallfbd.png)

Length = 12m, as that is the length of the bridge, and height = 3√3/2, as that is between 2 and 3 meters and allows for all bars to be length 3 meters. As there will be two trusses, each side only needs to support its own weight and 15kN. We model the 15kN at the center because this creates the largest forces at Ay and Dy due to balancing reactions.

![Joint analysis](/portfolio/assets/images/joint%20analysis.png)

To find the maximum force felt by the members in the truss, I needed to perform an analysis of joints to determine every force.

![Summary of forces](/portfolio/assets/images/forces.png)

Summary of the forces for easier later calculations. Additionally, as we have learned in class, a partially hollow circle proportionally loses less resistance against bending and stress than it saves in material, so to minimize weight while still meeting the factor of safety, the beams should be hollow tubes. Structural steel was chosen because it is not too heavy while still being able to handle high tensile and compressive forces.

![Factor of safety constraint](/portfolio/assets/images/FoS%20constraint.png)

The factor of safety constraint was calculated using the maximum force to find the minimum cross-sectional area.

![Deflection analysis and area](/portfolio/assets/images/Deflection%20analysis%20and%20area.png)

Following YouTube tutorials, the maximum deflection was calculated. Since the worst case has all the force at the center of the truss, the analysis was simplified without needing to repeat the truss geometry.

![Mass calculation](/portfolio/assets/images/mass.png)

Calculated the mass based on the hollow cylinder principle mentioned earlier.

![Final design](/portfolio/assets/images/final.png)

Final design with measurement specifications.

---

*AI Use Note: I used AI assistance to understand how to structure and format this project page in Markdown and Jekyll.*
