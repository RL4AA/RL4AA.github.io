---
title: "Accelerated Deep Reinforcement Learning for Fast Feedback of Beam Dynamics at KARA"
date: 2021-05-27
draft: false
tags: ["publication", "journal article", "kit", "kara", "ieee tns"]
categories: "Publications"
ShowToc: false
TocOpen: false
cover:
    image: imgs/wang2021accelerated.png
    alt: "Hardware solution  for RL control."
    caption: "Hardware solution  for RL control."
    relative: false
---

_**W. Wang<sup>1</sup>, M. Caselle<sup>1</sup>, T. Boltz<sup>1</sup>, E. Blomley<sup>1</sup>, M. Brosi<sup>1</sup>, T. Dritschler<sup>1</sup>, A. Ebersoldt<sup>1</sup>, A. Kopmann<sup>1</sup>, A. Santamaria Garcia<sup>1</sup>, P. Schreiber<sup>1</sup>, E. Bründermann<sup>1</sup>, M. Weber<sup>1</sup>, A.-S. Müller<sup>1</sup>, Y. Fang<sup>2</sup>**_

<sup>1</sup>Karlsruhe Insitute of Technology KIT, <sup>2</sup>Northwestern Polytechnical University

_IEEE Transactions on Nuclear Science_

## Abstract

Coherent synchrotron radiation (CSR) is generated when the electron bunch length is in the order of the magnitude of the wavelength of the emitted radiation. The self-interaction of short electron bunches with their own electromagnetic fields changes the longitudinal beam dynamics significantly. Above a certain current threshold, the micro-bunching instability develops, characterized by the appearance of distinguishable substructures in the longitudinal phase space of the bunch. To stabilize the CSR emission, a real-time feedback control loop based on reinforcement learning (RL) is proposed. Informed by the available THz diagnostics, the feedback is designed to act on the radio frequency (RF) system of the storage ring to mitigate the micro-bunching dynamics. To satisfy low-latency requirements given by the longitudinal beam dynamics, the RL controller has been implemented on hardware (FPGA). In this article, a real-time feedback loop architecture and its performance is presented and compared with a software implementation using Keras-RL on CPU/GPU. The results obtained with the CSR simulation Inovesa demonstrate that the functionality of both platforms is equivalent. The training performance of the hardware implementation is similar to software solution, while it outperforms the Keras-RL implementation by an order of magnitude. The presented RL hardware controller is considered as an essential platform for the development of intelligent CSR control systems.

**Read the paper:** [https://doi.org/10.1109/TNS.2021.3084515](https://doi.org/10.1109/TNS.2021.3084515)

**Contact:** -
