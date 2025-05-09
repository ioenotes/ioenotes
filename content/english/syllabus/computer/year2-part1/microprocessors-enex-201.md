---
title: "Microprocessors (ENEX201) - BCT II/I Syllabus"
meta_title: "Syllabus: Microprocessors (ENEX201) - BCT Year 2 Part 1 | IOE Notes"
description: "Detailed syllabus for Microprocessors (ENEX201), a second year, first part subject in the IOE BCT (Bachelor of Computer Engineering) program. Covers microprocessor architecture, programming, and interfacing techniques."
draft: false
image: "/images/syllabus/bct-syllabus.jpg"
author: "John Doe"
tags: ["BCT", "Computer Engineering", "tailwind"]
---

**Lecture**: 3  
**Tutorial**: 1  
**Practical**: 3  
**Year**: II  
**Part**: I  

## Course Objectives

The objective of this course is to familiarize students with assembly language programming, hardware and applications of microprocessors. The course provides students with a comprehensive understanding of microprocessor architecture, programming, and interfacing techniques, with a focus on the Intel 8085 and 8086 microprocessors. Students will gain theoretical and practical knowledge of microprocessor-based systems, covering essential topics such as computer organization, instruction sets, memory and I/O interfacing, interrupt mechanisms, and advanced architectural concepts.

---

## 1. Introduction (4 hours)

1.1 Introduction to microprocessors  
1.2 History of microprocessors  
1.3 Basic block diagram of a digital computer  
1.4 Microcomputer and microcontroller  
1.5 Bus organization of computer system  
1.6 Stored program concept (Von Neumann's architecture)  
1.7 Processing cycle of a stored program computer  

---

## 2. Intel 8085 Microprocessor (12 hours)

2.1 Features of 8085  
2.2 Internal architecture of 8085  
2.3 Pin configurations of 8085  
2.4 Instruction format and data format  
2.5 Addressing modes of 8085  
2.6 Instruction set of 8085  
2.7 Various programs in 8085  
  - 2.7.1 Simple programs with arithmetic and logical operations  
  - 2.7.2 Conditions and loops  
  - 2.7.3 Array and table processing  
  - 2.7.4 Decimal - BCD conversion  
  - 2.7.5 Multiplication and division  
2.8 Instruction cycle, machine cycle and T-cycle  
2.9 Timing diagrams of bus operations  

---

## 3. Intel 8086 Microprocessor (14 hours)

3.1 Features of 8086  
3.2 Internal architecture of 8086  
  - 3.2.1 BIU and components  
  - 3.2.2 EU and components  
  - 3.2.3 EU and BIU operations  
3.3 Segment and offset address  
3.4 Pin configurations of 8086  
3.5 Addressing modes of 8086  
3.6 Assembly language programming  
3.7 High level versus low level programming  
3.8 Assembly language syntax  
  - 3.8.1 Comments  
  - 3.8.2 Reserved words  
  - 3.8.3 Identifiers  
  - 3.8.4 Statements  
  - 3.8.5 Directives  
  - 3.8.6 Operators  
  - 3.8.7 Instructions  
3.9 EXE and COM programs  
3.10 Assembling, linking and execution  
3.11 One pass and two pass assemblers  
3.12 Interrupt services: INT 21H and INT 10H  
3.13 Various programs in 8086  
  - 3.13.1 Simple programs for arithmetic, logical, string and input/output  
  - 3.13.2 Conditions and loops  
  - 3.13.3 Array and string processing  
  - 3.13.4 ASCII and decimal numbers operation  
  - 3.13.5 Displaying numbers in decimal, binary and hexadecimal formats  

---

## 4. Microprocessor System (7 hours)

4.1 Memory classifications and hierarchy  
4.2 Interfacing I/O devices and memory with 8085  
  - 4.2.1 Address decoding  
  - 4.2.2 Unique and non-unique address decoding  
  - 4.2.3 I/O mapped I/O and memory mapped I/O  
  - 4.2.4 I/O address decoding with NAND and block decoders  
  - 4.2.5 Memory address decoding  
4.3 Parallel Interface  
  - 4.3.1 Modes: Simple, wait, single handshaking and double handshaking  
  - 4.3.2 Introduction to programmable peripheral interface (PPI)  
4.4 Serial Interface  
  - 4.4.1 Synchronous and asynchronous transmission  
  - 4.4.2 Serial interface standards: RS232, USB  
  - 4.4.3 Introduction to USART  

---

## 5. Interrupt Operations (5 hours)

5.1 Interrupt and its importance  
5.2 Polling vs interrupt  
5.3 Types of interrupts  
5.4 Interrupts in 8085 and interrupt instructions  
5.5 Interrupt service routine  
5.6 Interrupt processing in 8085  
5.7 Using programmable interrupt controllers (PIC)  
5.8 Interrupt in 8086 and interrupt vector table  
5.9 Interrupt processing in 8086  

---

## 6. Advanced Topics (3 hours)

6.1 Harvard architecture  
6.2 Accumulator based and register based architecture  
6.3 Hardwired and microprogrammed control unit  
6.4 RISC and CISC  
6.5 Introduction to multiprocessing/multitasking  
6.6 Digital signal processor  

---

## Tutorial

1. Assembly language programming with 8085  
2. Assembly language programming with 8086  
3. Input/output and memory address decoding  

Problems are solved, and students are assisted by the teacher to solve additional programming problems during tutorial classes.

---

## Assignment

Appropriate assignment problems should be given to students after the completion of each chapter.

---

## Practical

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

## References

1. Gaonkar, R. S. (2002), *Microprocessor Architecture, Programming and Applications with the 8085*, Prentice Hall  
2. Abel, P. (2000), *IBM PC Assembly Language and Programming*, 5th edition, Prentice Hall  
3. Hall, D. V. (1999), *Microprocessors and Interfacing: Programming and Hardware*, 2nd Edition, Tata McGraw Hill  
4. Stalling, W. (2009), *Computer Organization and Architecture*, Prentice Hall

---

**Contributions Welcome:**
If you find any discrepancies, have updated syllabus documents, or wish to contribute in any other way, please visit our general [contribution page on GitHub](https://github.com/ioenotes/ioenotes). For syllabus-specific updates, you can directly access the [syllabus content folder](https://github.com/ioenotes/ioenotes/tree/main/content/english/syllabus). Your help is invaluable in keeping this resource beneficial for all students!

For updates specific to this Microprocessors (ENEX201) syllabus page, you can [suggest an edit directly on GitHub](https://github.com/ioenotes/ioenotes/blob/main/content/english/syllabus/computer/year2-part1/microprocessors-enex-201.md). Your help is invaluable in keeping this resource beneficial for all students! 