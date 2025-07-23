# AIM:To study and implement C++ Bitwise Operators
## SOFTWARE REQUIRED:VS CODE 
### THEORY:
In C++, bitwise operators allow you to perform operations directly on the binary representations of integers. These operators are especially useful in low-level or system programming where performance and memory efficiency are crucial. Each integer is treated as a series of bits (0s and 1s), and bitwise operators manipulate them at that level.

Bitwise AND (&):
The Bitwise AND operator compares each bit of two integers. If both bits at the same position are 1, the result is 1; otherwise, it’s 0. This is useful when you want to check or filter out specific bits.

Bitwise OR (|):
The Bitwise OR operator compares corresponding bits of two integers. If at least one of the bits is 1, the result is 1. It’s commonly used to set specific bits to 1.

Bitwise XOR (^):
The Bitwise XOR (exclusive OR) operator returns 1 only if the corresponding bits of the two integers are different (i.e., one is 0 and the other is 1). It’s useful for toggling bits or detecting differences.

Bitwise NOT (~):
The Bitwise NOT is a unary operator that inverts every bit of the integer. So, 0 becomes 1, and 1 becomes 0. It essentially flips all bits in the binary representation.

Left Shift (<<):
The Left Shift operator moves the bits of a number to the left by a specified number of positions. This is equivalent to multiplying the number by 2 for each shift. For example, a << 2 multiplies a by 4.

Right Shift (>>):
The Right Shift operator moves the bits of a number to the right by a certain number of positions. Each shift divides the number by 2. So, a >> 1 is like dividing a by 2.

Implementation:
The Bitwise Operators are applied in the following practical examples to better understand their role and functionality in C++.

CONCLUSION: In this practical i learnt about how to use bitwise operaters and their implementation in C++

Conclusion:
This document and the included programs demonstrate how various bitwise operators work in C++. From basic logic operations to direct manipulation of individual bits, these tools are powerful when precision and control over data are needed.


