# EX 17 C Program to compare two strings without using strcmp().
## DATE:
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1. Start.
2. Define a variables.
3. Write program to compare two strings using nested for loop and if statement.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.  

## Program:
```
#include <stdio.h>
int main() {
 char str1[100], str2[100];
 int i = 0, flag = 0;
 scanf("%s", str1);
 scanf("%s", str2);
 while (str1[i] != '\0' || str2[i] != '\0') {
 if (str1[i] != str2[i]) {
 flag = 1;
 break;
 }
 i++; } 
if (flag == 0) 
printf("Strings are equal.\n");
else
 printf("Strings are not equal.\n");
 return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/fa7a0432-214b-4603-9b42-e8d2b3a09d52)

## Result:
Thus the program was executed and the output was verified successfully.
