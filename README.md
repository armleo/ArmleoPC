# ArmleoCPU
This is the core itself. It contains all the RTL and all the tests.

## ArmleoCPU_toolset
Prebuilt packages for Docker with predefined Yosys, Verilator, Icarus Verilog and RISCV GNU Toolchain used to do basic verification of ArmleoCPU.

# ArmleoPC
ArmleoPC is a repository containing all subprojects. There is no code or scripts on this top level repository

## ArmleoPC_zsbl
Zero stage boot loader. A simple assembler file which is used to reset register values and read data from SPI flash into boot memory

## ArmleoPC_opensbi
This is bootloader with all modifications to implement ArmleoPC support.

## ArmleoPC_qemu
QEMU modification to bring ArmleoPC support.

## ArmleoPC_sky130
Skywater130 tape out top project.