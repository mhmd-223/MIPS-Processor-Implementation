# MIPS Processor Implementation (Spring 2022)

This project was developed as part of the Computer Architecture course (CEE210/CEE216) during the Spring 2022 semester at the Faculty of Engineering, Electrical Engineering Department. The objective of the project was to design and implement a 16-bit MIPS-like processor using the Logisim simulator.

## Project Description

The MIPS processor implemented in this project follows a 16-bit instruction set architecture with R-type, I-type, and J-type instruction formats. It features seven 16-bit general-purpose registers (R1 to R7), with R0 hardwired to zero and inaccessible for writing. The processor includes a special-purpose 12-bit program counter (PC) and supports various operations such as arithmetic, logical, and memory-related instructions.

### Prerequisites

- Download and install Logisim simulator on your machine. You can find it at [http://www.cburch.com/logisim/](http://www.cburch.com/logisim/).

### Usage
1. Download this project and extract the files to a local directory.
2. Open Logisim simulator.
3. Open the processor circuit file (PROCESSOR.circ) from the extracted project directory (within SingleCycleProcessor.circ).
4. Upload the machine code into the ROM memory in the processor circuit. You can obtain the machine code by encoding instructions manually according to the provided instruction formats or by using the provided assembler (see next section).
5. Add any required data to RAM as necessary.
6. Press "CTRL+K" to run the simulation automatically.

## Assembler

I had worked on an assembler for this project to simplify the process of converting assembly code to machine code. The assembler takes assembly code as input and produces the corresponding machine code output.

**Note:** The assembler will be provided as a separate repository, which you can download and use in conjunction with this project.

## Documentation

For more detailed information about the MIPS processor implementation, including the instruction set architecture, memory organization, addressing modes, register file, and ALU, please refer to the provided PDF project description file (Project_Spring_2022).
