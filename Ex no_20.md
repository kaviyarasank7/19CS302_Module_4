# EX 20 C program to convert the given string to lowercase without using string functions.

## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm:
1. Start.
2. Define the required variable.
3. Convert the string to lowercase.
4. Read the value using scanf.
5. Print out the answer.
6. End..

## Program:
```
/*
Developed by: Kaviyarasan S
RegisterNumber:  212222060117
*/
#include <stdio.h>
#include <string.h>
int main()
{
  char str[30];
  
  scanf("%[^\n]", str);
  int i = 0;
  //convert capital letter string to small letter string
  while (str[i] != '\0')
  {
    if (str[i] > 64 && str[i] < 91) //or if(str[i]>='A' && str[i]<='Z')
      str[i] += 32;
    i++;
  }
  printf("Lower case String is:%s", str);
}
```

## Output:
<img width="1058" height="202" alt="image" src="https://github.com/user-attachments/assets/708fa749-41a2-4813-b776-f4d1116708e0" />


## Result:
Thus the program was executed and the output was verified successfully.
