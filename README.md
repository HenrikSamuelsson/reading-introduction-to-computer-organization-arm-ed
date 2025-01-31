# Reading Introduction to Computer Organization

Notes on the book Introduction to Computer Organization: ARM Edition, Robert G. Plantz, No Starch Press (2024).

## Abbreviations

List of abbreviations used in the book.

*CMOS*&#x2003;complementary metal-oxide semiconductor
*ISA*&#x2003;instruction set architecture  

## Introduction

A computer is a machine that can solve problems, by executing a program in the form of a sequence of *machine instructions*, part of the machines *instruction set architecture (ISA)*.

Programs are generally implemented by a programmer using a human friendly high-level language, rather than working directly with the ISA.

### Who the Book is For

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
4. Boolean Algebra - Boolean operators and tools for manipulation
5. Logic Gates - Electronics and logic gates