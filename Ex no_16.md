# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1. Start.
2. Define a variables a,b,c,min.
3. Write program to find minimum numbers.
4. Read the value using scanf. 
5. Ask the user to make an input.
6. Print out the answer.
7. End.  

## Program:
```
#include <stdio.h>
int main() {
float a, b, c, min;
scanf("%f%f%f", &a, &b, &c);
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min);
return 0;
}
```

## Output:

<img width="1151" height="220" alt="image" src="https://github.com/user-attachments/assets/27fd7695-7ab7-4f1b-a518-a59981501ff0" />


## Result:
Thus the program was executed and the output was verified successfully.
