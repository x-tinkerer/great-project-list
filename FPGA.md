# FPGA Best Projects

## YosysHQ/yosys
### https://github.com/YosysHQ/yosys
Yosys Open SYnthesis Suite.

This is a framework for RTL synthesis tools. It currently has extensive Verilog-2005 support and provides a basic set of synthesis algorithms for various application domains.

Yosys can be adapted to perform any synthesis job by combining the existing passes (algorithms) using synthesis scripts and adding additional passes as needed by extending the yosys C++ code base.


## YosysHQ/nextpnr

### https://github.com/YosysHQ/nextpnr
nextpnr -- a portable FPGA place and route tool

nextpnr aims to be a vendor neutral, timing driven, FOSS FPGA place and route tool.

Currently nextpnr supports:
- Lattice iCE40 devices supported by Project IceStorm
- Lattice ECP5 devices supported by Project Trellis
- Lattice Nexus devices supported by Project Oxide
- Gowin LittleBee devices supported by Project Apicula
- (experimental) Cyclone V devices supported by Mistral
- (experimental) Lattice MachXO2 devices supported by Project Trellis
- (experimental) a "generic" back-end for user-defined architectures

## SymbiFlow/prjxray
Documenting the Xilinx 7-series bit-stream format.


## matrix-io/xc3sprog
### https://github.com/matrix-io/xc3sprog
c3sprog is a suite of utilities for programming Xilinx FPGAs, CPLDs, and EEPROMs with the Xilinx Parallel Cable and other JTAG adapters under Linux. Used to program the FPGA of the MATRIX Creator/Voice via Raspberry Pi.


## ZYNQ-NVDLA
### https://github.com/LeiWang1999/ZYNQ-NVDLA
NVDLA (An Opensource DL Accelerator Framework) implementation on FPGA.

## tinyTPU
### https://github.com/jofrfu/tinyTPU
The aim of this project is to create a machine learning co-processor with a similar architecture as Google's Tensor Processing Unit. The implementation is resource-friendly and can be used in different sizes to fit every type of FPGA. This allows the deployment of this co-processor in embedded systems and IoT devices, but it can also be scaled up to be used in data centers and high-perfomance machines. The AXI interface allows usage in a variety of combinations. Evaluations were made on the Xilinx Zynq 7020 SoC.


## OpenTPU
### https://github.com/UCSBarchlab/OpenTPU
OpenTPU is an open-source re-implementation of Google's Tensor Processing Unit (TPU) by the UC Santa Barbara ArchLab.

The TPU is Google's custom ASIC for accelerating the inference phase of neural network computations.

Our design is based on details from Google's paper titled "In-Datacentre Performance Analysis of a Tensor Processing Unit" (https://arxiv.org/abs/1704.04760), which is to appear at ISCA2017. However, no formal spec, interface, or ISA has yet been published for the TPU.

The OpenTPU is powered by PyRTL (http://ucsbarchlab.github.io/PyRTL/).


## NPU_on_FPGA
### https://github.com/cxdzyq1110/NPU_on_FPGA
在FPGA上面实现一个NPU计算单元。 能够执行矩阵运算（ADD / ADDi / ADDs / MULT / MULTi / DOT等）、图像处理运算（CONV / POOL等）、非线性映射（RELU / TANH / SIGM等）。
- 优点:考虑到灵活性较强，易于修改网络结构，适用于实现小型CNN/RNN网络。
- 缺陷:由于指令串行执行、缺少Cache导致外存读写频繁，运算性能较低。