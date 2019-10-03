# ACSO

INPUT
STORE a
INPUT
STORE b
INPUT 
STORE c
loop, LOAD x
ADD multiply
STORE multiply
LOAD x
SUBT one
STORE x
SKIPCOND 400
JUMP loop
LOAD multiply
ADD one
JUMP loop
LOAD a
ADD multiply
STORE multiply
LOAD a
SUBT one
STORE a
SKIPCOND 400
JUMP loop
LOAD multiply
OUTPUT
HALT
a, Dec 0
b, Dec 0
c, Dec 0
one, Dec 1
multiply, Dec 0
x, Dec 2
