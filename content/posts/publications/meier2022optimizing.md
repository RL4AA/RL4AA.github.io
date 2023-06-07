---
title: "Optimizing a superconducting radio-frequency gun using deep reinforcement learning"
date: 2022-10-28
draft: false
tags: ["publication", "journal article", "simulation only", "hzb", "Universtiy of Kassel", "prab"]
categories: "Publications"
ShowToc: false
TocOpen: false
cover:
    image: imgs/meier2022optimizing.png
    alt: "Schema of the parameters’role within the learning loop."
    caption: "Schema of the parameters’role within the learning loop."
    relative: false
---

_**D. Meier<sup>1</sup>, L. V. Ramirez<sup>1</sup>, J. Völker<sup>1</sup>, J. Viefhaus<sup>1</sup>, B. Sick<sup>2</sup>, G. Hartmann<sup>1</sup>**_

<sup>1</sup>Helmholtz-Zentrum Berlin, <sup>2</sup>University of Kassel

_Physical Review Accelerators and Beams_

## Abstract

Superconducting photoelectron injectors are promising for generating highly brilliant pulsed electron beams with high repetition rates and low emittances. Experiments such as ultrafast electron diffraction, experiments at the Terahertz scale, and energy recovery linac applications require such properties. However, optimizing the beam properties is challenging due to the high number of possible machine parameter combinations. This article shows the successful automated optimization of beam properties utilizing an already existing simulation model. To reduce the required computation time, we replace the costly simulation with a faster approximation with a neural network. For optimization, we propose a reinforcement learning approach leveraging the simple computation of the derivative of the approximation. We prove that our approach outperforms standard optimization methods for the required function evaluations given a defined minimum accuracy.

**Read the paper:** [https://doi.org/10.1103/PhysRevAccelBeams.25.104604](https://doi.org/10.1103/PhysRevAccelBeams.25.104604)

**Contact:** -
