# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
 #include <stdio.h>
 #include <stdlib.h>
 #include <time.h>
 int main() {
 int i, n;
 srand(time(0));
 printf("Enter how many pseudorandom numbers you want to generate: ");
 scanf("%d", &n);
 printf("Generating %d pseudorandom numbers between 0 and 99:\n", n);
 for (i = 0; i < n; i++) {
 int randomNumber = rand() % 100;
 printf("%d ", randomNumber);
 }
 printf("\n");
 return 0;
 }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/15627e40-b409-4c78-8cbc-54d4be1668d6)


## RESULT:
The program is executed successfully.
