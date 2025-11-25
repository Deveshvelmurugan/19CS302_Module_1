# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
Start.
Declare three variable value of type int for marks.
Prompt the user to enter a value.
Read the value using scanf.
Find total and average.
Print the result
End.

## Program:
```
#include <stdio.h> 
int main() { 
    int sub1, sub2, sub3, total; 
    float average; 
    scanf("%d %d %d", &sub1,&sub2,&sub3); 
    total = sub1 + sub2 + sub3; 
    average = total / 3.0; 
    printf("\nTotal : %d\n", total); 
    printf("Average : %.2f\n", average); 
    return 0; 
} 
```

## Output:
<img width="398" height="170" alt="438155873-ef557452-87c6-4a46-8235-b0ec5919d0d5" src="https://github.com/user-attachments/assets/426f04a9-e01a-4c52-a0a8-045c1f2bb00d" />

## Result:
Thus the program was executed and the output was verified successfully.
Thus the program was executed and the output was verified successfully.
