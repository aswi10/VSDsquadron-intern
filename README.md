# VSDsquadron-intern

VSDsquadron mini🪄:

VSDSquadron, a cutting-edge development board based on the RISC-V architecture that is fully open-source.

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/051a3e2f-9448-48ad-b44f-ca39fcd5ddd5)


This board presents an exceptional opportunity for individuals to learn about RISC-V and VLSI chip design utilizing only open-source tools, starting from the RTL and extending all the way to the GDSII.

Key Features of RISC-V🪄:

🔖Open Source: The RISC-V ISA is open and free to use, allowing anyone to design, manufacture, and sell RISC-V-based chips and software without paying licensing fees.

🔖Modular Design: RISC-V's modular approach allows designers to implement only the parts of the ISA they need, making it highly adaptable to various applications.

🔖Extensibility: RISC-V supports custom extensions, enabling developers to add specialized instructions for their specific needs without conflicting with the base ISA.

RISC-V 64🪄:

The term riscv64 refers to the 64-bit implementation of the RISC-V architecture. This includes:

🔖64-bit Registers: The riscv64 architecture uses 64-bit wide general-purpose registers, allowing it to handle larger data sizes and address spaces compared to its 32-bit counterpart (riscv32).

🔖64-bit Addressing: With 64-bit addressing, riscv64 can address a much larger memory space, which is crucial for applications requiring large amounts of memory.

TASK-1👩‍💻

Before the task let's know about what is leafpad🤔

Use Cases🪄:

🔖Basic Text Editing: Ideal for users who need a simple editor for writing plain text, notes, or quick edits.

🔖Configuration Files: Useful for editing configuration files on Unix-like systems, where a lightweight editor is preferable.

🔖Scripting: Suitable for simple scripting tasks where advanced features are not necessary.

 you can install Leafpad using the following command:

![leafpad](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/28d3c359-4e7d-409d-9905-aedd09ac3f75)


 Step 1:
Install and launch the leafpad and write your C code

![VirtualBox_vsdworkshop_23_06_2024_16_55_01 code](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/e15b4bd0-3576-4808-ae7a-8c1ab36b5bd5)

Step 2:
In the Ubuntu terminal give the commands and execute

![VirtualBox-Output](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/ccbe366b-9868-48c3-b013-9d540893cff7)

Step 3:
In output for you C code is visible in the terminal

Step 4:
Launch your risc64 compiler

![RISCV64 complier](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/ee9b6d28-3f11-47f5-97e0-8ee29f170394)

Step 5:
Get the assembly code and calculate the data of the instruction set,Calculate using your calculator in programmer mode

![Calculation](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/283632ec-cca9-4bbf-bf69-491e494cce96)

TASK-2👩‍💻

🔖clock dividers provide an output clock signal that is a divided frequency of the input.

🔖They can also be used as clock buffers and make multiple copies of the output frequency.

🔖Clock divider devices, when used in divide-by-1 mode, can also function as a fanout buffer.

Step 1:
Open the terminal and launch the leafpad

Step 2:
Write the C program for clock cycle divider

![C code for clock divider](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/c5d25bc2-f0e6-4669-a9e2-c97e737cac6d)

Step 3:
We will get the output of for the given c code

![Output of clock divider](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/dc7c0818-82da-442f-a360-99704d2e0032)


Step 4:
Compile the code in the riscv64

![riscv64](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/2ddad0fb-4075-495e-ab94-8124e390a545)

Step 5:
Get the assembly code for the C code of clock cycle divider and do the calculations

![Assembly code-clock divider](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/fa256962-c995-4177-bbe4-043a21dfa4fe)

![Screenshot (138)](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/9000c479-6a36-45ca-a46e-9b56e6fc60ad)

TASK-3👩‍💻

🔖Spike is a functional RISC-V ISA (Instruction Set Architecture) simulator. It is used for running and testing RISC-V programs without needing physical hardware. It can be employed for debugging, testing, and validating software for RISC-V based systems.

🔖The Spike RISC-V ISA simulator is often used by developers to run and test their RISC-V programs in a simulated environment before deploying them to actual hardware. 

🔖This allows for catching errors and verifying functionality early in the development process.

Using the spike we can verify the risc-v

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/abf8a4c5-6782-4214-b522-1ca48e4a4f9c)

Step 1:
Open the terminal and launch the task 1 file
(i.e)sum1ton.c

Step 2:
In the riscv64 complilation open the spike

![spike 2](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/39456c72-0dea-40ca-b4b8-e23ba691d3b9)

![spike](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/ee71ee17-4f29-438c-b764-aca696fd8848)

Step 3:
Using the assembly code we can test for risc-v system

![assembly code -spike](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/cd01de8c-25dc-4cbc-a77f-63eec2fa9b99)

Step 4:
Do the calculations of the assembly code and verify the difference using calculator

![Screenshot (139)](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/64837b09-f4b8-4c2a-8072-9a2332244c19)
















