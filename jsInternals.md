# JavaScript Internals

## JavaScript Engine

A program that executes JavaScript code.

### The engine does 3 major things

- Parsing:- JavaScript code is read line by line and converted into Abstract syntax tree.
- Compilation (JIT):- Code compiled to machine code with JIT compilation.
- Execution:- Code is executed using Memory heap and call stack.

## Memory Heap

- Stores:
  - Objects
  - Functions
  - Variables
- Unstructured memory
- Garbage collected automatically

## Call Stack

A stack Data Structure that tracks:

    * Which function is currently running.
    * What function called what...

## JavaScript Runtime

- The runtime environment where JavaScript runs.
- It consist of:
  JS engine + Web APIs + Callback queues + Microtask queues + Event Loop
