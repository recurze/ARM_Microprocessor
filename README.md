## ARM_Microprocessor

1. This repo contains a [ARM](https://en.wikipedia.org/wiki/ARM_architecture) based CPU written in VHDL.

2. It is divided into 2 modules: datapath and controller, with each having their own submodules/entities.

## [Datapath](https://github.com/recurze/ARM_Microprocessor/tree/master/datapath)

1. Is a integrated design consisting of functional units:
 - ALU
 - Multipliers
 - Shifter
 - Register File, registers
 - Muxes and extenders.

2. ![Schematic]()

## [Controller](https://github.com/recurze/ARM_Microprocessor/tree/master/controller)

1. Controller determines the operation of the datapath, by passing control signals to various multiplexers. It controls the data flow through the datapath.

2. It consists of the following sub-modules:
 - Instruction Decode
 - Main Controller
 - ALU Controller
 - Branch Controller
 - ControlFSM

3. ![Schematic]()

## Software
