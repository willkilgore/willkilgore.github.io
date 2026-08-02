---
title: "Acrylic Bracket FEA Optimization"
excerpt: "Optimized an acrylic bracket using FEA to maximize stiffness- and strength-to-weight ratios under design constraints"
collection: portfolio
---

<table style="width:100%; text-align:center;">
  <tr>
    <td><img src="/images/fea_1.jpg" style="width:100%; max-width:220px; max-height:220px;"></td>
    <td><img src="/images/fea_3.JPG" style="width:100%; max-width:220px; max-height:220px;"></td>
  </tr>
  <tr>
    <td><em>Mesh Creation and Boundary Definition</em></td>
    <td><em>Final Cut Part for Validation</em></td>
  </tr>
</table>

## Timeline
Oct 2025 - Dec 2025

## Skills
- Finite Element Analysis (Abaqus) and Mesh Refinement
- Iterative Geometry Optimization Under Constraints
- Experimental Validation of Simulation

## Objectives
Optimize the geometry of an acrylic structural bracket to maximize strength-to-weight and stiffness-to-weight ratios within a fixed part envelope and loading condition, then validate the FEA predictions against physical test data.

## Overview
This was a group project completed as part of a class on deformable solids, in which I was responsible for the strength-to-weight optimization of an acrylic bracket. The project began with a fixed geometric envelope and loading condition, within which I built and meshed a model in the student edition of Abaqus. After applying boundary conditions and loading to represent the real-world use case, I iteratively refined the geometry — removing material from low-stress regions and reinforcing high-stress regions — using stress and displacement results from each FEA iteration to guide the next. The final design was laser-cut from acrylic and tested to failure to validate the simulation.

## Technical Details
- Assessed geometric restrictions to define the maximum allowable part envelope
- Applied a 400N load at upper cutout to represent the real-world use case, with boundary conditions fixed at lower cutouts
- Built a mesh with local seeding in high-stress regions to improve solution accuracy without excessive element count
- Iterated geometry across 10 design revisions, removing material from low-stress regions identified by stress contour plots while reinforcing high-stress concentration areas
- Reduced part mass by roughly 15% from original design while maintaining a minimum safety factor against yield
- Final geometry was laser-cut from acrylic and tested to failure; validating the FEA model to within 10%
