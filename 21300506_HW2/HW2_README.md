# Homework 2

# CNF Converter
This is an introduction of how to solve the **DNF converter** problem with C programming.

## Chapter 1. About the contents
1. `DNF converter.c` is C code.
2. `tree.h` is a header file for C code.
3. `input.txt` is an input file.

## Chapter 2. How to set an input.
You can use  `input.txt` with statement.
ex) `input.txt`
``` txt
(or a1 (not (or (not (or a2 a3)) a4)))
```
> `or` is  a disjunction.
> `and` is a conjunction.
> `not` is a negation.
> `aN` is propositional formula ( N is an integer).

## Chapter 4. How to run
> How to build?
```
make
```
or
```
gcc -o hw2.out -I hw2.h hw2.c
```
In the Debug mode, you can see which functions are executed.

```
gcc -DDEBUG -o hw2.out -I hw2.h hw2.c
```
> How to execute?
```
./hw2.out < input.txt
