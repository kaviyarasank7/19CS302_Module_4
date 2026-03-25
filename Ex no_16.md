# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm:
1. Start.
2. Define a variables a,b,c,min.
3. Write program to find minimum numbers.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End. 

## Program:
```
/*
Developed by: Kaviyarasan S
RegisterNumber:  212222060117
*/
#include <stdio.h>
int main() {
float a, b, c, min;
scanf("%f%f%f", &a, &b, &c);
// Finding minimum using conditional operator 
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min);
return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/0f34eb6e-9c2d-4f9b-805f-fac82611aae1)


## Result:
Thus the program was executed and the output was verified successfully.
