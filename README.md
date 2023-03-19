# IT1050-Tutorial-02

## Objectives : Convert C programs to C++
Use your Repl.IT account and use the Instructions provided by your Instructors to complete the Tutorial.  All instructions are in the GitHub classroom and Repl.it  for the Tutorial Questions for Week 02. Please submit your solutions by commiting code from Repl.it

## Exercise 1 - Calculations

Convert the C program given below which converts a length given in cm to inches to a C++ program.


Please Note that the input command in C++ is std::cin. This is a representation of the Keyboard.


e.g. 
```c
float data1;
int data2;
scanf("%f", &data1); --> std::cin >> data1;
scanf("%d", &data2); --> std::cin >> data2; 
```


You already know that ```printf()``` in C is ```std::cout``` in C++
e.g.
```
printf("Hello World") --> std::cout << "Hello World";
```

2.54cm = 1 inch

```c
#include <iostream>
int main() 
{
    float cm, inches;
    std::cout<<"Enter a length in cm : ";
     std::cin >>cm;
    inches = cm / 2.54;
      std::cout<<"Length in inches is"  <<" inches";
    
}   
   
```

## Exercise 2 - Selection


Convert the C program given below which calculates an employee's salary to a C++ program.

#include <iostream>
int main() 
{
    float cm, inches;
    std::cout<<"Enter a length in cm : ";
     std::cin >>cm;
    inches = cm / 2.54;
      std::cout<<"Length in inches is"  <<" inches";
    
}   
Input Type, Salary, otHours
```
Type = 1
OtRate = 1000
Type = 2
OtRate = 1500
Type = 3
OtRate = 1700
```


Please Note that the input command in C++ is std::cin. This is a representation of the Keyboard.

```c
#include <iostream>
int main()

{
   double salary, netSalary;
   int etype, otHrs, otRate;
    std::cout<<"Enter  Employee Type : ";
    std::cin >>etype;
    std::cout<<"Enter Salary  : ";
    std::cin >> salary;
    std::cout<<"Enter OtHrs : ";
   std::cin >>otHrs; 
   
 
    switch (etype) 
   {
   
      case 1 :
           std::cout<<"otRate = 1000";
          break;
      case 2 :
            std:: cout<<"otRate = 1500";
          break;
      default :
            std::cout<<" otRate = 1700";
          break;
          return 0;
      }
        netSalary = salary + otHrs* otRate;
   std::cout<< "Net Salary is"<< "netSalary";
}
    
   
   


 
```

## Exercise 3 - Repeatition


Convert the C program given below which calculates the Factorial of a number that you input from the keyboard to a C++ program.

Please Note that the input command in C++ is ```std::cin```. This is a representation of the Keyboard.

```c
#include <iostream>

long Factorial(int no);
long nCr(int n, int r);

int main() {
  int n, r;
  std::cout << "Enter a value for n ";
  std::cin >> n;
  std::cout << "Enter a value for r ";
  std::cin >> r;
  std::cout << "nCr = ";
  std::cout <<" nCr(n,r)";
  std::cout << std::endl;
}
```
 
## Exercise 4 - Functions
Write a program to calculate the function called nCr which is defined as
```
nCr = n!/ r!(n−r)!
```

Where n! is the factorial of n.

Implement the functions
```
long Factorial(int no);
long nCr(int n, int r);
```

Do not modify the main function.

```c
#include <iostream>

long Factorial(int no);
long nCr(int n, int r);

int main() {
  int n, r;
  std::cout << "Enter a value for n ";
  std::cin >> n;
  std::cout << "Enter a value for r ";
  std::cin >> r;
  std::cout << "nCr = ";
  std::cout <<" nCr(n,r)";
  std::cout << std::endl;
}
```

