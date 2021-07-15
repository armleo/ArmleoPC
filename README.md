# ArmleoPC
ArmleoPC is a repository containing links to all subprojects.

# ArmleoCPU
This is the core itself. It contains all the RTL and all the tests.  
See: https://github.com/armleo/ArmleoCPU

## ArmleoCPU_toolset
Prebuilt Docker image with predefined toolset used to do basic verification of ArmleoCPU.  
See: https://github.com/armleo/ArmleoCPU_toolset  
See: https://hub.docker.com/repository/docker/armleo/armleocpu_toolset  

## ArmleoPC_zsbl
Zero stage boot loader. A simple assembler file which is used to reset register values and read data from SPI flash into boot memory

## ArmleoPC_opensbi
This is bootloader with all modifications to implement ArmleoPC support.

## ArmleoPC_tests
This folder contains Linux boot flow tests.

## ArmleoPC_linux
Linux kernel with modifications to support peripherals in ArmleoPC

## ArmleoPC_qemu
QEMU modification to bring ArmleoPC support.  
See: https://github.com/armleo/ArmleoCPU_qemu

# ArmleoPC_sky130
Skywater130 tape out top project. When started according repository link will be added here.
