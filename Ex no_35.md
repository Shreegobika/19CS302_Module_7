# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE:
## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
Start. Define a variables. Write a program to read a file name from user and create that file and insert student roll numbers in to that file. Read the value using scanf. Ask the user to make an input. Print out the answer. End.

## Program:
```
/*
C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

#include <stdio.h> 
int main() 
{ 
FILE *p; 
char name[100]; 
int num; 
int id; 
char text[100]; 
float m; 
scanf("%s",name); 
scanf("%d",&num); 
p=fopen("name","w"); 
printf("%s Opened\n",name); 
{ 
scanf("%d %s %f",&id,text,&m); 
fprintf(p,"%d %s %f",id,text,m); 
} 
fclose(p); 
printf("Data added Successfully");  
*/
```

## Output:
<img width="572" height="338" alt="image" src="https://github.com/user-attachments/assets/8d6fe8d8-b183-4fcf-812a-84b188e3821d" />

## Result:
Thus the program was executed and the output was verified successfully.
