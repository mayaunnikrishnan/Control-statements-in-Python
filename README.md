# Control statements in Python

## Table of Contents

1. [Conditional Statements](#conditional-statements)
   - [if Statement](#if-statement)
   - [elif Statement](#elif-statement)
   - [else Statement](#else-statement)
   
2. [Looping Statements](#looping-statements)
   - [for Loop](#for-loop)
   - [while Loop](#while-loop)
   
3. [Control Flow Statements](#control-flow-statements)
   - [break Statement](#break-statement)
   - [continue Statement](#continue-statement)
   - [pass Statement](#pass-statement)
   
4. [Exception Handling](#exception-handling)
   - [try Block](#try-block)
   - [except Block](#except-block)
   - [finally Block](#finally-block)
   - [else Block](#else-block)

## Conditional Statements

a. **if Statement:**

- Used to execute a block of code if a specified condition is true.
- Basic structure involves checking a condition and, if true, executing the subsequent block of code.

b. **elif Statement:**

- Short for "else if", it allows for multiple conditions to be checked sequentially.
- If the initial if condition is false, the elif conditions are checked in order, executing the block of the first true condition.

c. **else Statement:**

- Executed if none of the preceding if or elif conditions are true.
- Serves as a default action when no other conditions are met.

## Looping Statements

a. **for Loop:**

- Iterates over a sequence (like a list, tuple, dictionary, set, or string).
- Executes a block of code for each item in the sequence.
  
b. **while Loop:**

- Repeatedly executes a block of code as long as a specified condition remains true.
- Used when the number of iterations is not known beforehand and depends on a condition.
  
## Control Flow Statements

a. **break Statement:**

- Exits the nearest enclosing loop immediately.
- Useful for terminating loops based on certain conditions.
  
b. **continue Statement:**

- Skips the current iteration and proceeds with the next iteration of the loop.
- Useful for skipping specific iterations based on conditions without terminating the entire loop.
  
c. **pass Statement:**

- Serves as a placeholder, indicating where code will eventually go.
- Does nothing when executed, used to maintain the program's structure during development.
  
## Exception Handling

a. **try Block:**

- Wraps code that might raise an exception.
- If an exception occurs, control is passed to the corresponding except block.
  
b. **except Block:**

- Defines how to handle specific exceptions.
- Multiple except blocks can be used to handle different exceptions in different ways.
  
c. **finally Block:**

- Contains code that will be executed no matter what, after the try and except blocks.
- Typically used for cleanup actions, like closing files or releasing resources.
  
d. **else Block:**

- Executed if the try block does not raise an exception.
- Used for code that should run only if no exceptions occur.
  
These control statements provide the tools necessary to manage the flow of a Python program, ensuring that it can respond to different conditions and handle errors gracefully.
