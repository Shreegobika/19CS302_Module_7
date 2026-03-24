# EX 33 C program to read a file name from user and create that file using fopen().
## DATE:
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
Start. Define a variables. Write a program to read a file name from user and create that file using fopen(). Read the value using scanf. Ask the user to make an input. Print out the answer. End.

## Program:
```
/*
C program to read a file name from user and create that file using fopen().

#include <stdio.h> 
int main()
{FILE *p;
char name[40]; 
scanf("%s",name);
p=fopen("name","w");
printf("%s File Created Successfully\n",name); 
printf("%s File Opened\n",name);
fclose(p);
printf("%s File Closed",name);
} 
*/
```

## Output:
<img width="1004" height="324" alt="image" src="https://github.com/user-attachments/assets/52b81e04-d139-450f-8874-60ef208a0fa7" />


## Result:
Thus the program was executed and the output was verified successfully.
