---
tags:
  - type/book
  - theme/programming
  - topic/operating-systems
aliases:
  - Computer Systems
title: "Computer Systems: A Programmer's Perspective"
author: "[[J. Stanley Warford]]"
category: Computers
total_page: "855"
publish_date: 2016-03-01
isbn13: "9781488672071"
isbn10: "1292101768"
link: https://play.google.com/store/books/details?id=JXfhCwAAQBAJ
status: to read
template_type: Book
---
![cover|150](http://books.google.com/books/content?id=JXfhCwAAQBAJ&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api)

# Computer Systems:  A Programmer's Perspective
by [[J. Stanley Warford]]

> [!summary] Summary
> Computer Systems, Fifth Edition provides a clear, detailed, step-by-step introduction to the central concepts in computer organization, assembly language, and computer architecture. It urges students to explore the many dimensions of computer systems through a top-down approach to levels of abstraction. By examining how the different levels of abstraction relate to one another, the text helps students look at computer systems and their components as a unified concept.

---

## My Core Takeaways
- 

## Notes & Quotes

### Chapter  1: A Tour Of Computer Systems
#### 1.1 Information Is Bits + Context
All information in a system is presented as a bunch of bits and the only thing that distinguishes between each object is the context at which we view them.

#### 1.2 Programs Are Translated by Other Programs into Different Forms
On a Unix system, the translation from source file to an *executable object file* is done by a *compiler driver*.

This translation is performed in four phases; *preprocessor*, *compiler*, *assembler*, and the *linker*, which are known collectively as the *compilation system.*

![[Pasted image 20250724204547.png]]

- *Preprocessing phase*. The compiler looks for the preprocessor modifies the C program according to directives that begin with `#` . The compiler essentially looks for the head file `stdio.h` and then insert the it directly into the program text. This results in another C program, typically with an `.i` suffix
- *Compilation Phase*. The compiler `.i` text files to the the `.s` text files, which contain the assembly code. 
- *Assembly Phase*. The assembler then translates the assembly into machine-language instructions and packages them into a form called *relocatable object program*. and stores result in a `.o`  object file.