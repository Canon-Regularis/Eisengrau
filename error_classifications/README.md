# Errors

A classification and reference of errors which can occur in Python and C++ programs.

The report covers errors from source processing through execution and termination.

## Scope

The report is restricted to:

* Python
* C++

The classification is language-independent where possible, with Python and C++ used to describe the concrete behaviour of each category.

## Contents

```text
01  Foundations
02  Lexical Errors
03  Syntax Errors
04  Name, Scope and Declaration Errors
05  Type Errors
06  Compile-Time Errors
07  Linking and Build Errors
08  Runtime Exceptions
09  Memory and Pointer Errors
10  Undefined Behaviour
11  Arithmetic and Numeric Errors
12  Container and Data Structure Errors
13  Resource and System Errors
14  I/O and Serialisation Errors
15  Concurrency Errors
16  Logic and Correctness Errors
17  Assertions, Panics and Termination
18  Python Error Hierarchy
19  C++ Error Taxonomy
20  Python vs C++
21  Detection and Recovery
22  Master Taxonomy
```

## Classification

Each error is described according to:

```text
Category
Subcategory
Cause
Detection stage
Detection mechanism
Program state
Python behaviour
C++ behaviour
Recoverability
Related errors
```

The report distinguishes between:

```text
Lexical errors
Syntax errors
Semantic errors
Type errors
Compile-time errors
Link-time errors
Runtime errors
Memory errors
Undefined behaviour
Logical errors
System errors
```

These categories are not necessarily mutually exclusive. An individual failure may have several classifications depending on whether it is considered by cause, detection stage, or observable behaviour.

## Detection stages

Errors are also classified by where they are detected:

```text
Source
  |
  +-- Lexer
  |
  +-- Parser
  |
  +-- Semantic analysis
  |
  +-- Type checking
  |
  +-- Compilation
  |
  +-- Linking
  |
  +-- Loading
  |
  +-- Runtime
  |
  +-- Operating system
```

## Python

The Python section covers the built-in exception hierarchy and related runtime failures.

Examples include:

```text
TypeError
ValueError
NameError
AttributeError
IndexError
KeyError
ImportError
ModuleNotFoundError
RuntimeError
MemoryError
RecursionError
OverflowError
OSError
AssertionError
SyntaxError
```

The hierarchy and behaviour of each exception are documented separately.

## C++

The C++ section covers:

```text
Compiler diagnostics
Linker errors
Standard library exceptions
Memory failures
Signals
Undefined behaviour
Implementation-defined behaviour
Unspecified behaviour
Runtime failures
```

C++ does not provide a single exception hierarchy corresponding to the full set of possible program errors. Compiler diagnostics, exceptions, operating-system failures and undefined behaviour are therefore treated separately.

## Python vs C++

Equivalent or related failures are compared where the two languages provide different mechanisms for detecting or reporting the same underlying problem.

For example:

```text
Concept                   Python              C++
---------------------------------------------------------------
Type mismatch             TypeError           Compile-time error
Invalid index             IndexError          std::out_of_range / UB
Missing key               KeyError            Container-specific behaviour
Null access               AttributeError      Undefined behaviour
Memory exhaustion         MemoryError         std::bad_alloc
Division by zero          ZeroDivisionError   Undefined behaviour / exception
Invalid argument          TypeError/ValueError std::invalid_argument
```

The comparison is based on semantics rather than matching names.

## Structure

Each classification contains an overview followed by individual error classes.

An individual entry generally contains:

```text
Definition
Classification
Conditions for occurrence
Detection
Python behaviour
C++ behaviour
Example
Recovery
Related errors
```