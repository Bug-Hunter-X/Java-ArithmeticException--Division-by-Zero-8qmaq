# Java ArithmeticException: Division by Zero

This repository contains a simple Java program that demonstrates an `ArithmeticException` caused by division by zero.  The `Bug.java` file contains the erroneous code, while `BugSolution.java` provides a corrected version.

## Bug Description
The program attempts to divide an integer variable by zero, which is an undefined operation in mathematics and results in an `ArithmeticException` at runtime. 

## Solution
The corrected version adds input validation to check if the divisor is zero before performing the division, preventing the exception.