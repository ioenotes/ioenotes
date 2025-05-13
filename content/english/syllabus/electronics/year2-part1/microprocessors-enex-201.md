---
title: "Microprocessors - BEI II/I Syllabus"
meta_title: "Syllabus: Microprocessors (ENEX 201) - BEI Year 2 Part 1 | IOE Notes"
description: "Detailed syllabus for Microprocessors (ENEX 201), a second year, first part subject in the IOE BEI program."
draft: false
image: "/images/syllabus/electronics-syllabus.jpg"
tags: ["BEI", "Electronics Engineering"]
subject: "Microprocessors"
subject_code: "ENEX 201"
---

**Lecture**: 3  
**Tutorial**: 1  
**Practical**: 3  
**Year**: II  
**Part**: I  

### Course Objectives
The objective of this course is to familiarize students with assembly language programming, hardware and applications of microprocessors. The course provides students with a comprehensive understanding of microprocessor architecture, programming, and interfacing techniques, with a focus on the Intel 8085 and 8086 microprocessors. Students will gain theoretical and practical knowledge of microprocessor-based systems, covering essential topics such as computer organization, instruction sets, memory and I/O interfacing, interrupt mechanisms, and advanced architectural concepts.

---

### 1. Introduction (4 hours)
- Introduction to microprocessors
- History of microprocessors
- Basic block diagram of a digital computer
- Microcomputer and microcontroller
- Bus organization of computer system
- Stored program concept (Von Neumann’s architecture)
- Processing cycle of a stored program computer

---

### 2. Intel 8085 Microprocessor (12 hours)
- Features of 8085
- Internal architecture of 8085
- Pin configurations of 8085
- Instruction format and data format
- Addressing modes of 8085
- Instruction set of 8085
- Various programs in 8085
  - Simple programs with arithmetic and logical operations
  - Conditions and loops
  - Array and table processing
  - Decimal - BCD conversion
  - Multiplication and division
- Instruction cycle, machine cycle and T-cycle
- Timing diagrams of bus operations

---

### 3. Intel 8086 Microprocessor (14 hours)
- Features of 8086
- Internal architecture of 8086
  - BIU and components
  - EU and components
  - EU and BIU operations
- Segment and offset address
- Pin configurations of 8086
- Addressing modes of 8086
- Assembly language programming
- High level versus low level programming
- Assembly language syntax
  - Comments
  - Reserved words
  - Identifiers
  - Statements
  - Directives
  - Operators
  - Instructions
- EXE and COM programs
- Assembling, linking and execution
- One pass and two pass assemblers
- Interrupt services: INT 21H and INT 10H
- Various programs in 8086
  - Simple programs for arithmetic, logical, string and input/output
  - Conditions and loops
  - Array and string processing
  - ASCII and decimal numbers operation
  - Displaying numbers in decimal, binary and hexadecimal formats

---

### 4. Microprocessor System (7 hours)
- Memory classifications and hierarchy
- Interfacing I/O devices and memory with 8085
  - Address decoding
  - Unique and non-unique address decoding
  - I/O mapped I/O and memory mapped I/O
  - I/O address decoding with NAND and block decoders
  - Memory address decoding
- Parallel Interface
  - Modes: Simple, wait, single handshaking and double handshaking
  - Introduction to programmable peripheral interface (PPI)
- Serial Interface
  - Synchronous and asynchronous transmission
  - Serial interface standards: RS232, USB
  - Introduction to USART

---

### 5. Interrupt Operations (5 hours)
- Interrupt and its importance
- Polling vs interrupt
- Types of interrupts
- Interrupts in 8085 and interrupt instructions
- Interrupt service routine
- Interrupt processing in 8085
- Using programmable interrupt controllers (PIC)
- Interrupt in 8086 and interrupt vector table
- Interrupt processing in 8086

---

### 6. Advanced Topics (3 hours)
- Harvard architecture
- Accumulator based and register based architecture
- Hardwired and microprogrammed control unit
- RISC and CISC
- Introduction to multiprocessing/multitasking
- Digital signal processor

---

### Tutorial (15 hours)
1. Assembly language programming with 8085
2. Assembly language programming with 8086
3. Input/output and memory address decoding
Problems are solved, and students are assisted by the teacher to solve additional programming problems during tutorial classes.

---

### Assignment
Appropriate assignment problems should be given to students after the completion of each chapter.

---

### Practical (45 hours)
1. Familiarization to programming kit and program entry/execution in kit
2. 8085 assembly language programming with data transfer instructions
3. 8085 assembly language programming with arithmetic instructions
4. 8085 assembly language programming with logical instructions
5. 8085 assembly language programming with branching and stack instructions
6. Miscellaneous and practical programming with 8085 such as multiplication/division
7. Familiarization with DEBUG and entry/executing programs
8. 8086 assembly language programming with simple programs and assemble link and execute programs
9. 8086 assembly language programming for input and output using INT 21H service
10. 8086 assembly language programming for display using INT 10H service
11. 8086 assembly language programs for various conditions and I/O operations
12. Lab test

---

### Final Examination
| Chapter | Hours | Marks distribution* |
|---------|-------|---------------------|
| 1       | 4     | 6                   |
| 2       | 12    | 15                  |
| 3       | 14    | 18                  |
| 4       | 7     | 12                  |
| 5       | 5     | 6                   |
| 6       | 3     | 3                   |
| **Total** | **45** | **60**             |

*There may be minor deviation in marks distribution.*

---

### References
1. Gaonkar, R. S. (2002). Microprocessor Architecture, Programming and Applications with the 8085. United Kingdom: Prentice Hall.
2. Abel, P. (2000). IBM PC Assembly Language and Programming (5th edition). United Kingdom: Prentice Hall.
3. Hall, D. V. (1999). Microprocessors and Interfacing: Programming and Hardware (2nd Edition). Tata McGraw Hill.
4. Stalling, W. (2009). Computer Organization and Architecture. Prentice Hall.
