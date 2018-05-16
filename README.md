Byter
=====


Byter is an 8-bit computer built entirely out of 7400 series HC and HCT integrated circuits.
It features a 16-bit address bus, 64Kb RAM, up to 32Kb ROM, 8 input ports, and 8 output ports.
The custom architecture includes a hardware stack pointer, program counter, accumulator,
index register (page + offset). CPU clock rates of up to 1Mhz are supported, however by
default the clock is scaled down to 2KHz. 

Peripherals are mapped to the following ports:


* **I0**: 8-bit timer
* **I1**: Keypad scan
* **O0**: LCD data
* **O1**: LCD control
* **O2**: Keypad mask


This repository contains a rudimentary assembler, an eeprom uploader and a microcode generator.

![CPU](https://raw.githubusercontent.com/nandor/byter/master/docs/byter.JPG)

![PRG](https://raw.githubusercontent.com/nandor/byter/master/docs/prog.JPG)
