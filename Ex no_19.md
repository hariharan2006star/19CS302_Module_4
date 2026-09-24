# EX 19C program to perform the basic left and right shift operation.  
## DATE:
## AIM:
To write a C program to perform the basic left and right shift operation.  

## Algorithm

1.Start the program and read an integer value a from the user.

2.Perform the left shift operation using c = a << 2.

3.Perform the right shift operation using d = a >> 2.

4.Display the results of both left shift and right shift operations.

5.Stop the program.

## Program:
```
#include<stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    int c=a<<2;
    int d=a>>2;
    printf("After Left Shift Operation value of a is:%d\n",c);
    printf("After Right Shift Operation value of a is:%d\n",d);
    return 0;
    
}
```

## Output:

<img width="679" height="164" alt="Screenshot 2026-03-19 142827" src="https://github.com/user-attachments/assets/60586c32-134c-4c3d-8516-30d406d0016c" />


## Result:
Thus the program was executed and the output was verified successfully.
