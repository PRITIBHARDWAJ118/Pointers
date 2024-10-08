# Pointers
## Aim: 
This repository contains basics of Pointers in C++.
## Theory:
Pointers are variables that store the memory address of another variable. They provide a way to directly access and manipulate memory, which can be used to create dynamic data structures, manage arrays, pass parameters to functions by reference, and more. 
### Declaration and Initialization
Pointers are declared using the * operator, and they must be initialized to point to a valid memory location.
SYNTAX: int *ptr; // ptr is a pointer to an integer
Initialization:   int a = 5;
                   ptr = &a; // ptr now holds the address of a
### Pointers and arrays:
An array name in C/C++ is essentially a pointer to the first element of the array. Pointers can be used to iterate over arrays or to pass them to functions.
SYNTAX: int arr[3] = {1, 2, 3};
       int *ptr = arr[0]/arr; // ptr holds the adress of 1st element of array,hence it can be iterated by incremented by one 
## Call by value and Call by reference:
In C++, functions can be invoked using two primary methods: Call by Value and Call by Reference.
## Call by value 
Call by Value means that when a function is called, the actual parameters are copied into the formal parameters of the function. This means that any changes made to the parameters inside the function do not affect the original arguments passed by the caller.
Example: int area(int length,int bredth)
## Call by reference 
Call by Reference means that when a function is called, the actual parameters are passed by reference. This allows the function to modify the original variables since the function operates directly on the references to the actual arguments.
Example: double (int *length, int *bredth)
## Differences between call by value and call by reference 
1. Memory Usage:
Call by Value: Requires more memory because it creates a copy of each argument.
Call by Reference: More memory-efficient as it does not create copies but instead uses references.

2. Performance:
Call by Value: Can be slower for large data structures (like large arrays or structs) because of the overhead of copying.
Call by Reference: Generally faster for large data structures since it avoids the overhead of copying.

3.Safety:
Call by Value: Safer in some cases because it ensures that the original data cannot be accidentally modified.
Call by Reference: More powerful but can lead to unintended side effects if the original data is modified unintentionally.

4. Use Cases:
Call by Value: Best for cases where you do not want the function to modify the original arguments.
Call by Reference: Useful when you need the function to modify the original arguments or when you want to pass large data structures without the overhead of copying.


## Output:

1. Pointers basics(declaring and initializing arrays)
   
![image](https://github.com/user-attachments/assets/5bad461a-11ea-4fd9-ae75-2d9e78dd7564)





2. Acessing arrays using pointers 


![image](https://github.com/user-attachments/assets/2414ac6a-c1f5-4972-9c6b-3a37132f837a)




3. Call by value 

![image](https://github.com/user-attachments/assets/c2660e70-9d4b-4a00-893c-c231be8b086c)



4. Call by reference 


![image](https://github.com/user-attachments/assets/dbf635bf-58a8-4ec5-9d80-b41d42c11073)




## Conclusion:
We learnt about basics of pointers, using pointers in arrays and call by value and call by reference. 




