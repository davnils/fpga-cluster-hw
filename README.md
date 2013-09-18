# FPGA Cluster prototype hardware

<img src="https://github.com/davnils/fpga-cluster-hw/raw/master/images/joined.jpg" />

This repository contains prototype hardware used when exploring cluster concepts in connection to FPGAs.
Circuit boards are four layer routed on heavily constrained dimensions in order to fit a tight budget.
Connectors and components (sensitive decoupling caps specifically) are mounted on both outer layers.

Schematics and gerber files are provided for a platform containing:

* Two Altera Stratix II FPGAs
* ARM LPC uC
* Ethernet controller
* Unified power supply powered by 12V ATX

## Story
A few years ago (~2010) I was researching FPGA hardware and possible uses within computational intensive tasks.
This hardware platform was developed, and manufactured, but unfortunately got stuck due to insufficient funds when troubleshooting BGA-mounted FPGAs.
In connection to the hardware a software platform was developed (not part of this repository).
Eventually the goal was to have a FPGA cluster platform capable of hot-swapping and scheduling of various tasks.

Since I wasn't able to complete the project, these files have been made available in order to inspire or help others.

## Status
The PCBs have been manufactured and basic electrical testing has been performed.

## File formats
Gerbers are ready for manufacturing or manual inspection.
Schematics are in a format specific to Altium Designer.
