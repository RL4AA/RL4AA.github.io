---
title: "Basic Reinforcement Learning Techniques to Control the Intensity of a Seeded Free-Electron Laser"
date: 2020-05-09
draft: false
tags: ["publication", "journal article", "fermi fel", "University of Trieste", "Elettra Sincrotrone Trieste", "electronics"]
categories: "Publications"
ShowToc: false
TocOpen: false
cover:
    image: imgs/bruchon2020basic.png
    alt: "Simple scheme of the FERMI FEL seed laser alignment set up."
    caption: "Simple scheme of the FERMI FEL seed laser alignment set up."
    relative: false
---

_**N. Bruchon<sup>1</sup>, G. Fenu<sup>1</sup>, G. Gaio<sup>2</sup>, M. Lonza<sup>2</sup>, F. H. O’Shea<sup>2</sup>, F. A. Pellegrino<sup>1</sup>, E. Salvato<sup>1</sup>**_

<sup>1</sup>University of Trieste, <sup>2</sup>Elettra Sincrotrone Trieste

_Electronics_

## Abstract

Optimal tuning of particle accelerators is a challenging task. Many different approaches have been proposed in the past to solve two main problems—attainment of an optimal working point and performance recovery after machine drifts. The most classical model-free techniques (e.g., Gradient Ascent or Extremum Seeking algorithms) have some intrinsic limitations. To overcome those limitations, Machine Learning tools, in particular Reinforcement Learning (RL), are attracting more and more attention in the particle accelerator community. We investigate the feasibility of RL model-free approaches to align the seed laser, as well as other service lasers, at FERMI, the free-electron laser facility at Elettra Sincrotrone Trieste. We apply two different techniques—the first, based on the episodic Q-learning with linear function approximation, for performance optimization; the second, based on the continuous Natural Policy Gradient REINFORCE algorithm, for performance recovery. Despite the simplicity of these approaches, we report satisfactory preliminary results, that represent the first step toward a new fully automatic procedure for the alignment of the seed laser to the electron beam. Such an alignment is, at present, performed manually.

**Read the paper:** [https://www.mdpi.com/2079-9292/9/5/781](https://www.mdpi.com/2079-9292/9/5/781)

**Contact:** [Niky Bruchon](mailto:niky.bruchon@phd.units.it)
