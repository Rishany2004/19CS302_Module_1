# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Calculate the number of years using the formula
6. End

## Program:
```
#include <stdio.h>
int main() {
    int age;
    printf("Enter your age: ");
    scanf("%d", &age);
    if (age >= 21)
    {
        printf("You are eligible for marriage.\n");
    } else {
        printf("You are not eligible for marriage.\n");
    }
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/668d3a80-bf03-4a4a-adee-2e7e73c2cc98)

## Result:
Thus the program was executed and the output was verified successfully.
