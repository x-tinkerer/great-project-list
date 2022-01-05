
## pulpissimo
### https://github.com/pulp-platform/pulpissimo
PULPissimo is the microcontroller architecture of the more recent PULP chips, part of the ongoing "PULP platform" collaboration between ETH Zurich and the University of Bologna - started in 2013.

PULPissimo, like PULPino, is a single-core platform. However, it represents a significant step ahead in terms of completeness and complexity with respect to PULPino - in fact, the PULPissimo system is used as the main System-on-Chip controller for all recent multi-core PULP chips, taking care of autonomous I/O, advanced data pre-processing, external interrupts, etc. The PULPissimo architecture includes:

- Either the RI5CY core or the Ibex one as main core
- Autonomous Input/Output subsystem (uDMA)
- New memory subsystem
- Support for Hardware Processing Engines (HWPEs)
- New simple interrupt controller
- New peripherals
- New SDK


## USTC-RVSoC
### https://github.com/bigzz/USTC-RVSoC
一个用 SystemVerilog 编写的，基于 RISC-V 的，普林斯顿结构的 SoC.