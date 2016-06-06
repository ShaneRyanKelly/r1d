This is a simple compiler written in C designed to support a number of functions
 and operations. This compiler compiles to a 16-bit assembly language for a simple
 register-oriented architecture. 

Compared to it's cousin, r1.c, the r1d compiler utilizes numerous optimization 
techniques in it's source code in order to cut down on compile time, program execution time, and total number of microcode instructions outputted by the compiler. Techniques utilized by r1d to boost efficiency include reusing temporary labels over the course of operations, the use of constant-folding in arithmetic operations, and the deletion of unneccessary temporary variables. These optimizations included in r1d.c make it a 'smart compiler'.

The compiler may be compiled from the r1d.c source
 code found in this directory. S3.s is the input file for the compiler which
 includes unary plus, addition, subtraction, and multiplication operations as well
 as a println() output function. A previous version of this compiler, r1c.c is also included in this directory.

The output file, S3.a is included to demonstrate the compiler's capabilities and
 output.
