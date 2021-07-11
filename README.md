# ArmleoPC
ArmleoPC is a repository containing all subprojects.

# ArmleoCPU
This is the core itself. It contains all the RTL and all the tests.

## ArmleoCPU_toolset
Prebuilt Docker image with predefined Yosys, Verilator, Icarus Verilog and RISCV GNU Toolchain used to do basic verification of ArmleoCPU.
See: https://github.com/armleo/ArmleoCPU_toolset

## ArmleoPC_zsbl
Zero stage boot loader. A simple assembler file which is used to reset register values and read data from SPI flash into boot memory

## ArmleoPC_opensbi
This is bootloader with all modifications to implement ArmleoPC support.

## ArmleoPC_tests
This folder contains Linux boot flow tests.s

## ArmleoPC_qemu (submodule)
QEMU modification to bring ArmleoPC support.

# ArmleoPC_sky130
Skywater130 tape out top project. When started according repository link will be added here.


# Getting started
Run following to install all subdirectories:

```
git submodule update --init --recursive
```