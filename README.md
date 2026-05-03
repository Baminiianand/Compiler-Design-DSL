 DSL Compiler Simulation (Extended) – C Project

 Project Overview

This project implements a **mini compiler simulation** for a simple **Domain-Specific Language (DSL)** using the C programming language. It demonstrates how a compiler processes input through different phases such as lexical analysis, syntax analysis, semantic analysis, and intermediate code generation.

 Objective

* To simulate the working of a compiler
* To understand different compiler phases
* To process simple arithmetic and assignment statements

Input Program

The program internally uses the following statements:

```
a = 3
b = 7
c = a + b
d = c * 2
```

Compiler Phases Implemented

 1. Lexical Analysis

* Identifies tokens:

  * Identifiers → a, b, c, d
  * Constants → 3, 7, 2
  * Operators → +, *

 2. Syntax Analysis

* Checks structure of statements:

  * Assignment statements
  * Arithmetic expressions

 3. Semantic Analysis

* Verifies:

  * Variable types (integers)
  * Valid operations

 4. Intermediate Code Generation

* Generates simplified representation:

```
t1 = a + b
c = t1
t2 = c * 2
d = t2
```

 5. Execution

* Performs actual computation:

  * c = 10
  * d = 20

 Output

The program displays:

* Compiler phase outputs
* Intermediate code
* Final computed values
* Success message

Technologies Used

* **Programming Language:** C
* **Library:** stdio.h

 Project Structure

```
Compiler-Design-DSL/
├── src/
│   └── RegNo_Name_HoT.c
├── docs/
│   └── Explanation.pdf
├── output/
│   └── execution.png
├── test/
│   └── input.txt
└── README.md
```

 How to Run

1. Open the `.c` file in Dev-C++ / Code::Blocks
2. Compile the program
3. Run the executable
4. View output in console

 Key Features

* Simulates real compiler workflow
* Structured phase-by-phase output
* Simple and easy to understand
* Suitable for beginners

Conclusion

This project successfully demonstrates how a compiler processes a program through multiple stages. It provides a clear and practical understanding of compiler design concepts using simple arithmetic operations.

Done by

**Name: Bamini A Reg no: RA2311026050248 Course: B.Tech CSE-AIML**
