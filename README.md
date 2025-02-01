# Reading Introduction to Computer Organization

Notes on the book Introduction to Computer Organization: ARM Edition, Robert G. Plantz, No Starch Press (2024).

## Resources

Links related to the book:

[The publishers page about the book.](https://nostarch.com/introcomputerorgforarm)  
[The authors page about the book.](https://rgplantz.github.io/itco_ARM/)  
[amazon.com page about the book.](https://www.amazon.com/Introduction-Computer-Organization-Robert-Plantz/dp/1718502745)  


## Abbreviations

List of abbreviations used in the book:

*CMOS*&#x2003;complementary metal-oxide semiconductor
*ISA*&#x2003;instruction set architecture  

## Introduction

A computer is a machine that can solve problems, by executing a program in the form of a sequence of *machine instructions*, part of the machines *instruction set architecture (ISA)*.

Programs are generally implemented by a programmer using a human friendly high-level language, rather than working directly with the ISA.

### Who the Book Is For

The book teaches low-level details about how computers work.

Knowledge in a high-level programming language is assumed, the book focuses on underlying low-level *assembly language*, that translates directly to machine instructions.

Writing in assembly is harder than writing in a high level programming language such as C, which is also used in the book.

### About the Book

Will learn by going hands-on with inexpensive easy to find hardware.

#### The Programming in the Book

Content is based on the ARM AArch64 architecture.

Platform used is the 64-bit Raspberry Pi OS running on Raspberry Pi 3 and Raspberry Pi5.

Will mostly use C and some C++, as high-level programming language.

C standard library is used to be able to have the applications use screen and keyboard.

#### Why Read This Book?

Book gives low-level knowledge, beneficial for:

- Helping us write better programs in a high-level programming language
- Doing systems programming such as operating systems and compilers
- Embedded systems development
- Having an easier time reading ARM manuals

#### Chapter Organization

Three main parts, with different focuses:

1. Mathematics and logic
2. Hardware
3. Software

First part providing a foundation to later understand how software controls the hardware.

The chapters in the book are:

1. Setting the Stage - Computer fundamentals and discussion on tools setup
2. Data Storage Formats - How number and characters are stored
3. Computer Arithmetic - Addition and subtraction of integers
4. Boolean Algebra - Boolean algebra and tools for working within this field
5. Logic Gates - Electronics followed by logic gates
6. Combinatorial Logic Circuits - Simple logic circuits without memory; adders, decoders, multiplexers
7. Sequential Logic Circuits - Logic circuits with built-in memory; with an state
8. Memory - The different types of computer memory
9. Central Processing Unit - The unit that executes instructions and its registers
10. Programming in Assembly Language - Both as output from a compiler and hand written assembly
11. Inside the `main` function - Register access, position-independent code, the call stack
12. Instruction Details - Instructions at the bit level and how addressing works
13. Control Flow Constructs - How to achieve flow control such as `while`, `for` and `if`-`else` in assembly
14. Inside Subfunctions - How the various variable types are connected to functions and how a stack frame is constructed
15. Special Uses of Subfunctions - Recursion also access to functions of the CPU hidden away by high-level languages
16. Instructions - Bitwise logic, multiplication, and division instructions
17. Data Structures - How arrays and structs are implemented at the assembly level
18. Object-Oriented Programming - Structs as objects in C++
19. Fractional Numbers - Fixed and floating point numbers representation
20. Input/Output - How to work with memory mapped I/O, especially on the Raspberry Pi, both in C and assembly
21. Exceptions and Interrupts - Introduction to exceptions and interrupts on the AArch64 architecture

### Efficient Use of the Book

The author aims to provide an efficient learning experience.

There are exercises called "Your Turn"' to practice, solutions to most of these can then be found at [Solutions to Your Turn Exercises](https://rgplantz.github.io/itco_ARM/).

Approach to work with the exercises:

1. Get hands on trying yourself
2. If step 1 fails then peek the solution
3. Return to step 1. and fix the solution

Prefer to type in the code yourself, and don't just copy paste the code.

Use the same hands on approach on he math chapters, do the math by hand, don't use a calculator or on-line service.

Next step is chapter 1, that discusses major parts of a computer and how to work with the Raspberry Pi.

## Chapter 1 - Setting the Stage

Will start by introducing a separation of computers into three different subsystems, setting a framework for further discussions.

The chapter will also discuss set up of the programming environment to be used in the rest of the book.