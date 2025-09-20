# Task 1
We start by modeling the entire RISC-V processor using C code. This C model acts as a high-level specification of how the processor should behave. We compile and run applications on this model using tools like RISC-V GCC to make sure it works correctly.

Once we're confident the C model is accurate, we move on to writing the actual hardware description in Verilog. The Verilog code for the processor only contains what is part of the processor’s instruction set and core logic. Peripherals and other modules (called IP blocks) are kept separate and reused as needed.

These IP blocks can include analog components, macros, or gate-level netlists that are proven and ready to use. By integrating the processor core with these peripherals and IP blocks, we create the full System on Chip (SoC).

Finally, to ensure everything works as expected, we run the same applications on the Verilog hardware model and check that the output matches the behavior of the C specification model.

Key Differences Between Microcontroller and Microprocessor

Microcontroller: A complete system on one chip, including CPU, memory, and peripherals. Used for embedded, specific tasks. Low cost and power-efficient.

Microprocessor: Only the CPU core; needs external memory and peripherals to work. More powerful and flexible, used in PCs and complex systems.


# Task 2
## magic

<img width="1512" height="920" alt="Screenshot from 2025-09-21 02-59-38" src="https://github.com/user-attachments/assets/9721d9b7-c7b1-47f1-8bc8-f5a2f62f8ad3" />

## ngspice

<img width="842" height="530" alt="Screenshot from 2025-09-21 02-54-14" src="https://github.com/user-attachments/assets/480ba1fc-5e04-4f7b-9c17-bc73d15d0e65" />

## yosys

<img width="842" height="420" alt="Screenshot from 2025-09-21 02-24-30" src="https://github.com/user-attachments/assets/59defdc4-e232-47cb-a2b5-936ec22331ab" />

## IVerilog

<img width="842" height="530" alt="Screenshot from 2025-09-21 02-26-43" src="https://github.com/user-attachments/assets/eca198ef-a7cf-4050-b092-d4f393bbf3a7" />

## openlane

<img width="654" height="616" alt="image" src="https://github.com/user-attachments/assets/24f7250b-ec82-49d4-975e-32edb8234368" />

## gtkwave

<img width="1124" height="695" alt="image" src="https://github.com/user-attachments/assets/79c27f64-f5f8-4d0b-9166-6cf01ff3a0b2" />
