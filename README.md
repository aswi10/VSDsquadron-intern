# VSDsquadron-intern

**VSDsquadron mini🪄:**

VSDSquadron, a cutting-edge development board based on the RISC-V architecture that is fully open-source.

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/051a3e2f-9448-48ad-b44f-ca39fcd5ddd5)


This board presents an exceptional opportunity for individuals to learn about RISC-V and VLSI chip design utilizing only open-source tools, starting from the RTL and extending all the way to the GDSII.

**Key Features of RISC-V🪄:**

🔖Open Source: The RISC-V ISA is open and free to use, allowing anyone to design, manufacture, and sell RISC-V-based chips and software without paying licensing fees.

🔖Modular Design: RISC-V's modular approach allows designers to implement only the parts of the ISA they need, making it highly adaptable to various applications.

🔖Extensibility: RISC-V supports custom extensions, enabling developers to add specialized instructions for their specific needs without conflicting with the base ISA.

**RISC-V 64🪄:**

The term riscv64 refers to the 64-bit implementation of the RISC-V architecture. This includes:

🔖64-bit Registers: The riscv64 architecture uses 64-bit wide general-purpose registers, allowing it to handle larger data sizes and address spaces compared to its 32-bit counterpart (riscv32).

🔖64-bit Addressing: With 64-bit addressing, riscv64 can address a much larger memory space, which is crucial for applications requiring large amounts of memory.

# **TASK-1👩‍💻**

Before the task let's know about what is leafpad🤔

Use Cases🪄:

🔖Basic Text Editing: Ideal for users who need a simple editor for writing plain text, notes, or quick edits.

🔖Configuration Files: Useful for editing configuration files on Unix-like systems, where a lightweight editor is preferable.

🔖Scripting: Suitable for simple scripting tasks where advanced features are not necessary.

 you can install Leafpad using the following command:

![leafpad](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/28d3c359-4e7d-409d-9905-aedd09ac3f75)


* Step 1:
Install and launch the leafpad and write your C code

![VirtualBox_vsdworkshop_23_06_2024_16_55_01 code](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/e15b4bd0-3576-4808-ae7a-8c1ab36b5bd5)

* Step 2:
In the Ubuntu terminal give the commands and execute

![VirtualBox-Output](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/ccbe366b-9868-48c3-b013-9d540893cff7)

* Step 3:
In output for you C code is visible in the terminal

* Step 4:
Launch your risc64 compiler

![RISCV64 complier](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/ee9b6d28-3f11-47f5-97e0-8ee29f170394)

* Step 5:
Get the assembly code and calculate the data of the instruction set,Calculate using your calculator in programmer mode

![Calculation](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/283632ec-cca9-4bbf-bf69-491e494cce96)

# **TASK-2👩‍💻**

🔖clock dividers provide an output clock signal that is a divided frequency of the input.

🔖They can also be used as clock buffers and make multiple copies of the output frequency.

🔖Clock divider devices, when used in divide-by-1 mode, can also function as a fanout buffer.

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/fa0c3039-2e8e-4a5f-9340-88e011312701)

The C code can be taken using any AI tool

* Step 1:
Open the terminal and launch the leafpad

* Step 2:
Write the C program for clock cycle divider

![C code for clock divider](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/c5d25bc2-f0e6-4669-a9e2-c97e737cac6d)

* Step 3:
We will get the output of for the given c code

![Output of clock divider](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/dc7c0818-82da-442f-a360-99704d2e0032)


* Step 4:
Compile the code in the riscv64

![riscv64](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/2ddad0fb-4075-495e-ab94-8124e390a545)

* Step 5:
Get the assembly code for the C code of clock cycle divider and do the calculations

![Assembly code-clock divider](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/fa256962-c995-4177-bbe4-043a21dfa4fe)

![Screenshot (138)](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/9000c479-6a36-45ca-a46e-9b56e6fc60ad)

# **TASK-3👩‍💻**

**Key Features of Spike🪄:**

🔖Spike is a functional RISC-V ISA (Instruction Set Architecture) simulator. It is used for running and testing RISC-V programs without needing physical hardware. It can be employed for debugging, testing, and validating software for RISC-V based systems.

🔖The Spike RISC-V ISA simulator is often used by developers to run and test their RISC-V programs in a simulated environment before deploying them to actual hardware. 

🔖This allows for catching errors and verifying functionality early in the development process.

Using the spike library we can verify the risc-v

* Step 1:
Open the terminal and launch the task 1 file
(i.e)sum1ton.c

* Step 2:
In the riscv64 complilation open the spike

![spike 2](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/39456c72-0dea-40ca-b4b8-e23ba691d3b9)

![spike](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/ee71ee17-4f29-438c-b764-aca696fd8848)

* Step 3:
Using the assembly code we can test for risc-v system

![assembly code -spike](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/cd01de8c-25dc-4cbc-a77f-63eec2fa9b99)

* Step 4:
Do the calculations of the assembly code and verify the difference using calculator

![Screenshot (139)](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/64837b09-f4b8-4c2a-8072-9a2332244c19)

# **TASK-4👩‍💻**

"Identify various RISC-V instruction type (R, I, S, B, U, J) and exact 32-bit instruction code in the instruction type format for below RISC-V instructions

ADD r1, r2, r3

SUB r3, r1, r2

AND r2, r1, r3

OR r8, r2, r5

XOR r8, r1, r4

SLT r10, r2, r4

ADDI r12, r3, 5

SW r3, r1, 4

SRL r16, r11, r2

BNE r0, r1, 20

BEQ r0, r0, 15

LW r13, r11, 2

SLL r15, r11, r2

Upload the 32-bit pattern on Github"

**1.R-Type instruction:** R-type (Register-type) instruction. R-type instructions are used for arithmetic and logical operations that require all operands to be located in registers.

The general format of an R-type instruction is:

opcode rs rt rd shamt funct

**📍Fields:**

* opcode: Operation code (always 000000 for R-type instructions in MIPS).

* rs: Source register (the first operand).

* rt: Source register (the second operand).

* rd: Destination register (where the result is stored).

* shamt: Shift amount (used for shift operations, otherwise 0).

* funct: Function code (specifies the exact operation to be performed).

Example: MIPS assembly instruction for addition

add $t1, $t2, $t3

**2.I-Type instruction:** I-type (Immediate-type) instruction. I-type instructions are used for operations that involve an immediate value (a constant), memory access operations, and branch instructions.

The general format of an I-type instruction is:

opcode rs rt immediate

**📍Fields:**

* opcode: Operation code (specifies the operation to be performed).

* rs: Source register (one operand).

* rt: Target register (where the result is stored, or another operand).

immediate: Immediate value (a constant value or address offset).

Example: MIPS assembly instruction for adding an immediate value

addi $t1, $t2, 10

**3.S-Type instruction:** S-type (Store-type) instruction. These instructions are used for storing data from a register into memory. 

The general format of an S-type instruction in RISC-V is:

opcode rs2 rs1 imm

**📍Fields:**

* opcode: Operation code (specifies the operation to be performed, such as 'sw' for store word).

* rs2: Source register 2 (contains the data to be stored).

* rs1: Source register 1 (base register for calculating the memory address).

* imm: Immediate value (offset used in address calculation, split into two parts in the instruction encoding).

Example: RISC-V assembly instruction for storing a word

sw x2, 12(x1)

**4.B-Type instruction:** B-type (Branch-type) instruction. These instructions control the flow of execution by conditionally branching to another part of the program based on the comparison of register values.

The general format of a B-type instruction in RISC-V is:

opcode rs1 rs2 imm

**📍Fields:**

* opcode: Operation code (specifies the branch operation).

* rs1: Source register 1 (one of the registers to be compared).

* rs2: Source register 2 (the other register to be compared).

* imm: Immediate value (branch offset, split into several parts in the instruction encoding).

Example: RISC-V assembly instruction for a branch if equal:

beq x1, x2, label

**5.U-Type instruction:** U-type (Upper Immediate-type) instruction. These instructions involve large immediate values, often used for addressing or for creating large constants. The U-type format is used for instructions that load a 20-bit immediate value into a register.

The general format of a U-type instruction in RISC-V is:

opcode rd imm

**📍Fields:**

* opcode: Operation code (specifies the operation to be performed).

* rd: Destination register (where the result is stored).

* imm: Immediate value (a 20-bit immediate value).

Example: Common U-type instructions in RISC-V are LUI (Load Upper Immediate) and AUIPC (Add Upper Immediate to PC).

LUI (Load Upper Immediate)

The LUI instruction loads a 20-bit immediate value into the upper 20 bits of the destination register, with the lower 12 bits set to zero.

lui x1, 0x12345

**6.J-Type instruction:** J-type (Jump-type) instruction. These instructions are designed for jump operations, where the program counter (PC) is set to a new address, allowing for function calls and unconditional jumps.

The general format of a J-type instruction in RISC-V is:

opcode rd imm

**📍Fields:**

* opcode: Operation code (specifies the operation to be performed).

* rd: Destination register (where the return address is stored, if applicable).

* imm: Immediate value (a 20-bit signed offset for the jump target address).

Example: Common J-type instructions in RISC-V are JAL (Jump and Link) and JALR (Jump and Link Register).

JAL (Jump and Link)

The JAL instruction jumps to the address specified by the immediate value and saves the return address (PC + 4) in the destination register.

jal x1, 0x12345

**RISC-V INSTRUCTION TYPE AND 32-BIT:**

* **ADD r1, r2, r3:**
  
opcode: 000000

rs: 00010

rt: 00011

rd: 00001

shamt: 00000

funct: 100000

Binary number:00000000010000110000100000100000 

32 bit pattern:0x00430820 in hexadecimal.

* **SUB r3, r1, r2:**

opcode: 000000

rs: 00001

rt: 00010

rd: 00011

shamt: 00000

funct: 100010

Binary number:00000000001000100001100000100010 

32 bit pattern:0x00221822

* **AND r2, r1, r3:**

opcode: 000000

rs: 00001

rt: 00011

rd: 00010

shamt: 00000

funct: 100100

Binary number:00000000001000110001000000100100 

32 bit number:0x00430824

* **OR r8, r2, r5:**

opcode: 000000

rs: 00010

rt: 00101

rd: 01000

shamt: 00000

funct: 100101

Binary number:00000000010010100101000000100101 

32 bit number:0x0128425

* **XOR r8, r1, r4:**

opcode: 000000

rs: 00001

rt: 00100

rd: 01000

shamt: 00000

funct: 100110

Binary number:0000000000100100010000000100110 

32 bit pattern:0x00420826

* **SLT r10, r2, r4:**

opcode: 000000

rs: 00010

rt: 00100

rd: 01010

shamt: 00000

funct: 101010

Binary number:00000000010010010100000000101010 

32 bit pattern:0x0124282A

* **ADDI r12, r3, 5:**

opcode for ADDI: 001000

rs: 00011

rt: 01100

immediate: 0000000000000101   

Binary number:00100000011011000000000000000101 

32 bit pattern:0x206C0005

* **SW r3, r1, 4:**

opcode for SW: 101011

base: 00001 

rt: 00011 

offset: 0000000000000100

Binary number:10101100001000110000000000000100 

32 bit pattern:0xAC630004

* **SRL r16, r11, r2:**

rs: r11 -> 01011 

rt: r2 -> 00010 

rd: r16 -> 10000 

Binary number:000000 01011 00010 10000 00011 000010

32 bit pattern:0x00B02803

* **BNE r0, r1, 20:**

opcode: 000101

rs: 00000

rt: 00001

immediate: 0000000000010100

Binary number:000101 00000 00001 0000000000010100

32 bit pattern:0x14010014

* **BEQ r0, r0, 15:**

opcode for BEQ: 000100 

rs: r0 -> 00000

rt: r0 -> 00000

immediate: 15 (decimal) -> 0000000000001111

Binary number:000100 00000 00000 0000000000001111

32 bit pattern:0x1000000F

* **LW r13, r11, 2:**

opcode for LW: 100011

rs: r11 -> 01011

rt: r13 -> 01101

immediate: 2 (decimal) -> 0000000000000010

Binary number:100011 01011 01101 0000000000000010

32 bit pattern:0x8B6A0002

* **SLL r15, r11, r2:**

opcode: 000000

rs: r11 -> 01011 

rt: r15 -> 01111 

rd: 00000 

shamt: Value in r2, interpreted as a 5-bit binary representation

Binary number:000000 01011 00000 01111 00011 000000

32 bit pattern:0x00B0001C

# **TASK-5👩‍💻**
Here with the help of RISC-V!!

* We are going to observe the functional simulation and the output waveforms using the verilog netlist and testbench

* For the verilog netlist and the testbench we can refer the reference repo 

* Lets clone the reference repository with the command

**git clone https://github.com/vinayrayapati/rv32i.git aswi_project**

* The reference repo is cloned to my project 

**cd aswi_project**

![aswi](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/2009ce4e-468f-44c2-9950-06d3a8109586)

**VERILOG TEST BENCH**

![tb](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/1b810503-bbd4-40e0-adaa-8d614e95a5c3)

* To run and simulate the verilog code use the command

_**iverilog -o rv32i_simulation iiitb_rv32i.v iiitb_rv32i_tb.v**_

* To see the waveform in the gtkwave use the command

_**gtkwave iiitb_rv32i.vcd**_

**GTKWAVE WINDOW**

![gtk](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/bfe6d15c-cb23-4149-b078-4e79779c41c6)

## Analysing the output waveforms of the instructions

* INSTRUCTION 1: ADD r1,r2,r3
  
![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/570c66ff-c1e2-4f1f-8cf3-62bf76354da5)

* INSTRUCTION 2: SUB r3,r1,r2

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/e4173918-aac1-40eb-928e-169974f0e09b)

*INSTRUCTION 3: AND r2,r1,r3

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/fd15449e-fb12-48bb-89da-e6fb926aa687)

*INSTRUCTION 4: OR r8,r2,r5

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/33748904-9b66-4440-a246-3e6892997302)

*INSTRUCTION 5: XOR r8,r1,r4

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/6936fe97-5301-486c-b14d-b53f6a3dd502)

*INSTRUCTION 6: SLT r10,r2,r4

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/1d477acd-fbbf-4cca-8516-e92f771138f3)

*INSTRUCTION 7: ADDI r12,r3,5

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/f05c35ce-79f2-4359-9429-0f10ed58c6f1)

*INSTRUCTION 8: BEQ r0,r0,r15

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/58430f16-0403-46bd-84aa-88c614cf02bb)

*INSTRUCTION 9: BNE r0,r1,20

![image](https://github.com/aswi10/VSDsquadron-intern/assets/173608392/7e8cff2a-15c2-469b-b497-c34a9f5d7108)

# TASK-5👩‍💻

## CLOCK CYCLE DIVIDER:CRAFTING A DIGITAL CLOCK DIVIDER CIRCUIT



















































