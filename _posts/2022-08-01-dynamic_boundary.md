---
layout: post
title: Mantle Convection with a dynamic lithosphere boundary
date: 2022-08-01
Author: Lan Hu
tags: [work diary]
comments: false
toc: true

---

*Advisor: Wei Leng	06/2022–08/2022*



## Background

One of the theories to explain the origin of multi-plate tectonics proposes that the generation of plates can be caused by changes in the thickness of lithosphere during the Earth's thermal evolution. We designed a model of mantle convection with a dynamic lithosphere boundary to justify this theory.



## Methods

1. Conducted **numerical modeling** of Earth's mantle convection with cylindrical geometry; 
2. **Wrote a plugin** to set the lithosphere boundary at a fixed temperature using ASPECT; 
3. Tested different Ra number; 
4. Compared results with cases without the dynamic lithosphere boundary



## Main Conclusions

1. The lithosphere thickness (under this definition) does change with time under steady state, but its amplitude is small (~5km when Ra~1e7), which is not sufficient to cause rift. 
2. Introducing a dynamic lithosphere boundary produces minor perturbations in thermal evolution.
