# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1.Start the program. 

2.Read the input string from the user
. 
3.Traverse each character of the string until the null terminator is reached. 

4.If the character is uppercase (between 'A' and 'Z'), convert it to lowercase by adding 32. 

5.Print the converted string and end the program.
## Program:
```
#include <stdio.h>

int main() {
    char str[1000];
    int i = 0;
    fgets(str, sizeof(str), stdin);

    while(str[i] != '\0') {
        if(str[i] >= 'A' && str[i] <= 'Z') {
            str[i] = str[i] + 32; 
        }
        i++;
    }

    printf("%s", str);

    return 0;
}
```

## Output:
<img width="797" height="167" alt="image" src="https://github.com/user-attachments/assets/4cd3724a-e7cc-4f2b-a507-c3e15bebe0e0" />

## Result:
Thus the program was executed and the output was verified successfully.
