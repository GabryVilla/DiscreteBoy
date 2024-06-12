# DiscreteBoy project 

## Why this project?
The objective of this project is to design a central processing unit (CPU) and make it with discrete Mosfet and other discrete components on a PCB.
This project is for learning purposes, and it's cool to build a CPU with discrete components.

## How is this project organized?

I decided to create three main directories.
1) Memory directory: In the memory directory, I will put every circuit with regard to memory.
2) CPU directory: I decided to divide the CPU into 4 subdirectories (ALU, control unit, CPU register, video card). 
Furthermore, every subdirectory has: 
a subdirectory with an explanation of how the logic circuit works.
a subdirectory with the logisism file and the logical circuit working.
a subdirectory with the schematic 
Note: Inside the schematics, all the logic is made with Mosfet and discrete components.
(Example: the full-adder subdirectory has its own directory with an explanation, logic circuit, and schematic.)
3) Complete directory: In the complete directory, all the schematics will be united into only one schematic and board.

## CPU characteristics

DiscreteBoy architecture is based on Von Neumann architecture and RISCV.
The aritmetic logic unit (ALU) can perform mathematical aritmetic operations (sum, subtraction, multiplication, and division). and boolean operation (and, nand, or, nor, xor, shift, load).
performance characteristics:
- 64-bit register and ALU
- internal video card (VGA protocol)

## licence 
This project is totally open source, so don't worry; take it and try to make something cool. 
