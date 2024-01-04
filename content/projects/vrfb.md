---
title: "A 3D model of a vanadium redox flow battery (VRFB) electrode" # in any language you want
description: "Master's thesis | Guide : Prof Dayadeep Monder, IIT Bombay | 2019"
draft: False
weight: 101
summary: "Master's Thesis, IIT Bombay"
---

Inspired by a course on fuel cells, I approached Prof Dayadeep Monder to start research on Mixed Ionic-Electronic Conductors. Impressed by my work, Prof Monder guided me in completing my master's thesis at IIT Bombay, "A 3D model of a vanadium redox flow battery (VRFB) electrode” using COMSOL - a culmination of my interests in both programming and simulation-related fields. It involved a 3D, stationary simulation of the negative electrode of a VRFB.

Briefly I :
-  I setup the fuel cell physics in COMSOL, with different boundary conditions for electrolyte inlet (circular vs whole surface)
- Used COMSOL's inbuilt adaptive mesh to discretise the problem
- Applied mass conservation, charge conservation and momentum conservation at each mesh point. Specifically, I used the Nernst-Planck equation for mass conservation and Brinkman equation for momentum conservation.
- Using COMSOL's inbuilt finite difference solver and mesh refinement, I simulated the 3D model.

(Senistivity analysis):
- Once the problem was setup, I varied various input parameters like SoC and inlet concentration to see the effect on the cell potential
- Compared and contrasted this analysis with the 2D simulations

I also made a lab visit to IIT Madras to see the experimental side of this research and gained various insights, along with understanding the differences in simulations and real-world experiments.

I defended my master's thesis and ended up with a grade of 9.58/10.