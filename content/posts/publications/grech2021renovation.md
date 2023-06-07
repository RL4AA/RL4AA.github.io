---
title: "Renovation of the beam-based feedback systems in the LHC"
date: 2021-09-01
draft: false
tags: ["publication", "phd thesis", "lhc", "University of Malta"]
categories: "Publications"
ShowToc: false
TocOpen: false
cover:
    image: imgs/grech2021renovation.png
    alt: "Best PPO agent. Action is deterministic."
    caption: "Best PPO agent. Action is deterministic."
    relative: false
---

_**L. Grech**_

University of Malta

_PhD thesis_

## Abstract

The Large Hadron Collider (LHC) at the European Organization for Nuclear Research (CERN) is the largest synchrotron built to date, having a circumference of approx- imately 27km. The LHC is able to accelerate two counter-rotating proton and/or heavy-ion beams up to 7 TeV per charge. These highly energetic beams are contained inside a vacuum chamber with an inner diameter of 80 mm by means of strong mag- netic fields produced by superconducting magnets. A beam cleaning and machine protection system is in place to prevent high-energy halo particles from impacting and heating the superconducting magnets.

Due to the tight tolerances on the beam trajectory imposed by the beam cleaning and machine protection system, the LHC was the first accelerator to require automatic beam-based feedback control. Until the LHC Run 2, this was implemented by the Beam-Based Feedback System (BBFS) which was mainly responsible for collecting beam measurements from various types of beam instrumentation and calculating the corrections in the current of corrector magnets throughout the whole length of the LHC.

Throughout the years of LHC operation, some of the original BBFS functionality became deprecated and fell into disuse. Various minor upgrades were performed, how- ever, without a systematic redesign of the BBFS the code became difficult to maintain. The BBFS also suffered from a computational bottleneck during the calculation of the optics matrices used by the BBFS controllers. A feasibility study was performed to assess whether Hardware Acceleration (HA) in the form of Graphical Processing Units (GPUs) would improve the performance. It was found that the use of GPUs was not necessary and as a result the hardware upgrade for the BBFS could be finalised. Following this was the redesign and implementation of a more streamlined BBFS called BFCLHC. This work was done in collaboration with BE-OP-LHC and was designed with a more intuitive interface. A new feature called Function Players was imple- mented at the request of the LHC operators, which allows certain BFCLHC settings to be automated.

The Base-Band Q (tune) (BBQ) system is responsible for estimating the values of the horizontal and vertical tunes in both beams of the LHC. It was found that noise harmonics were perturbing the tune estimates and consequently causing the Tune Feedback (QFB) within the BBFS to behave erroneously. In this work, new tune estimation algorithms were developed to improve upon the accuracy of the BBQ system. To aid with this development, a simulation procedure was set up which mimics the frequency spectra obtained by the BBQ system. Two algorithmic approaches were proposed which take into consideration the location of the noise harmonics. A data-driven approach was also attempted where a combination of simulated and real frequency spectra were used to train a neural network to predict the value of the tune from a BBQ spectrum. It was observed that the data-driven approach improves upon the stability of the tune estimates in the presence of noise harmonics.

The use of Reinforcement Learning (RL) in beam-based feedback control systems was considered since it offers the possibility of optimal control, regardless of any dy- namical changes in the machine. Since this work was performed during the LHC Long Shutdown 2 (LS2), the control problem present in the BBFS was formulated in a sim- ulation environment called QFBEnv that allowed RL agents to be trained offline. The linear beam optics models used in the standard Proportional-Integral (PI) controllers of the BBFS were used to simulate the response of the LHC. In particular, the perfor- mance of several RL agents in the task of tune correction were assessed in detail and run through different failure scenarios. All the tests performed showed that certain RL agents can achieve a better performance than a standard PI controller, also in the presence of actuator failures. The possibility of using RL in the orbit feedback was also considered and discussed.

**Read the paper:** [https://www.um.edu.mt/library/oar/handle/123456789/104427](https://www.um.edu.mt/library/oar/handle/123456789/104427)

**Contact:**
[Leander Grech](mailto:leander.grech.14@um.edu.mt)
