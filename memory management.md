# Lesson 9 - C++ Memory Management Basics

## What is Memory Management?

Memory management can be defined as the process to manage a computer's memory.
Example: Assigning memory to programs, variables, etc., so that it doesn't affect the overall performance.

## Why we need memory management?

Memory management is requiered to avoid wastage of memory and to make sure allocation takes place efficiently.

During the declaration of arrays, sometimes the exact memory is not known to us, and that is why we declare an array
of max size, which results in memory wastage.

To avoid such a case, we use memory allocation.

## Memory Allocation and Deallocation in C++

Programming languages like Java, Python, etc., have the compiler that manages the memory allocation.

In the case of C++, the allocation and deallocation of memory are done manually.

In C++, there are two operators that are used for the allocation and deallocation of memory.

1) new operator
2) delete operator

## C++ new operator

The new operator in C++ is used for dynamic memory allocation.

The new operator is responsible for the creation of the object.

Syntax:
	PointerVariable = new datatype;

Syntax for arrays:
	PointerVariable = new datatype[size];

In case of arrays, the new keyword returns the address of first element. 

## C++ delete operator

The delete operator in C++ is used for deallocation of memory or for releasing of memory space.

Once the memory is no longer required, then we have to deallocate the memory using the delete operator.

Syntax:
	delete PointerVariable;

Syntax for arrays:
	delete [] Pointervariable;

## Adavantages of the new operator

- new oeprator can be overloaded

- the return type of new is of the type for which the memory was allocated

- It automatically computes the size of the data object

- It can initialize object while creating a memory for it