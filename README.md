# Reading Introduction to Computer Organization

Notes on the book Introduction to Computer Organization: ARM Edition, Robert G. Plantz, No Starch Press (2024).

## Abbreviations

List of abbreviators used in the book.

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

Book gives low-level knowledge which is good for:

- Helping us write better programs in a high-level programming language
- Doing systems programming such as operating systems and compilers
- Embedded systems development
- Having an easier time reading ARM manuals
