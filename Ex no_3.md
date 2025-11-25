# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
Start.
Declare the variables.
Prompt the user to enter a value.
Read the value using scanf.
Calculate the number of years using the formula:
End .

## Program:
```
#include <stdio.h> 
#include <math.h> 
int main() 
{ 
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r); 
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n)); 
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci); 
return 0; 
}
```

## Output:
<img width="852" height="247" alt="438159349-fc4e3c25-2b86-451b-9ed7-a7b0692f4185" src="https://github.com/user-attachments/assets/f162dbc5-bb30-4cde-b130-238e3a8a1553" />

## Result:

Thus the program was executed and the output was verified successfully.
Thus the program was executed and the output was verified successfully.
