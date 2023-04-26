---
title: "Real-time artificial intelligence for accelerator control: A study at the Fermilab Booster"
date: 2021-10-18
draft: false
tags: ["publication", "journal article", "fermilab"]
categories: "Publications"
ShowToc: false
TocOpen: false
weight: 10
cover:
    image: imgs/stjohn2021realtime.png
    alt: "Schematic view of the GMPS control environment."
    caption: "Schematic view of the GMPS control environment."
    relative: false
---

_**J. St. John, C. Herwig, D. Kafkes, J. Mitrevski, W. A. Pellico, G. N. Perdue, A. Quintero-Parra, B. A. Schupbach, K. Seiya, N. Tran, M. Schram, J. M. Duarte, Y. Huang, R. Keller**._ Fermi National Accelerator Laboratory, Thomas Jefferson National Accelerator Laboratory, University of California San Diego, Pacific Northwest National Laboratory, Columbia University. _Physical Review Accelerators and Beams._

## Abstract

We describe a method for precisely regulating the gradient magnet power supply (GMPS) at the Fermilab Booster accelerator complex using a neural network trained via reinforcement learning. We demonstrate preliminary results by training a surrogate machine-learning model on real accelerator data to emulate the GMPS, and using this surrogate model in turn to train the neural network for its regulation task. We additionally show how the neural networks to be deployed for control purposes may be compiled to execute on field-programmable gate arrays (FPGAs), and show the first machine-learning based control algorithm implemented on an FPGA for controls at the Fermilab accelerator complex. As there are no surprise latencies on an FPGA, this capability is important for operational stability in complicated environments such as an accelerator facility.

**Read the paper:** [https://journals.aps.org/prab/abstract/10.1103/PhysRevAccelBeams.24.104601](https://journals.aps.org/prab/abstract/10.1103/PhysRevAccelBeams.24.104601)

**Contact:** [Jason St. John](mailto:stjohn@fnal.gov)
