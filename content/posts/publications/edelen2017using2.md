---
title: "Using Neural Network Control Policies For Rapid Switching Between Beam Parameters in a Free Electron Laser"
date: 2017-08-25
draft: false
tags: ["publication", "conference proceedings", "surrogate model", "Colorado State University", "Element Aero", "Fermilab", "LANL", "University of Twente", "neurips workshop"]
categories: "Publications"
ShowToc: false
TocOpen: false
cover:
    image: imgs/edelen2017using2.png
    alt: "General setup for the neural network model."
    caption: "General setup for the neural network model."
    relative: false
---

_**A. L. Edelen<sup>1</sup>, S. G. Biedron<sup>2</sup>, J. P. Edelen<sup>3</sup>, S. V. Milton<sup>4</sup>, P. J. M. van der Slot<sup>5</sup>**_

<sup>1</sup>Colorado State University, <sup>2</sup>Element Aero, <sup>3</sup>Fermi National Accelerator Laboratory, <sup>4</sup>Los Alamos National Laboratory, <sup>5</sup>University of Twente

_Workshop on Deep Learning for Physical Sciences at the Conference on Neural Information Processing Systems 2017_

## Abstract

Free Electron Laser (FEL) facilities often must accommodate requests for a varietyof electron beam parameters in order to supply scientific users with appropriatephoton beam characteristics. This usually requires skilled human operators to tunethe machine. In principle, a neural network control policy that is trained on a broadrange of machine operating states could be used to quickly switch between theserequests without substantial need for human intervention. We present preliminaryresults from an ongoing simulation study in which a neural network control policyis investigated for rapid switching between beam parameters in a compact THzFEL that exhibits nonlinear electron beam dynamics. To accomplish this, we firsttrain a feed-forward neural network to mimic a physics-based simulation of theFEL. We then train a neural network control policy by first pre-training it as aninverse model (using supervised learning with a subset of the simulation data) andthen training it more extensively with reinforcement learning.  In this case, thereinforcement learning component consists of letting the policy network interactwith the learned system model and backpropagating the cost through the modelnetwork to the controller network.

**Read the paper:** [https://ml4physicalsciences.github.io/2017/files/nips_dlps_2017_16.pdf](https://ml4physicalsciences.github.io/2017/files/nips_dlps_2017_16.pdf)

**Contact:**
[Auralee Edelen](mailto:auralee.l.morin@gmail.com)
