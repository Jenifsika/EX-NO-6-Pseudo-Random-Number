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
 
int main() 
{     int n, i; 
 
    // Seed the random number generator     srand(time(0)); 
 
    printf("Enter the number of random numbers to generate: ");     scanf("%d", &n); 
 
    printf("Random numbers are:\n"); 
    for(i = 0; i < n; i++) 
    { 
        printf("%d\n", rand()); 
    } 
 
    return 0; 
} 

```
# OUTPUT:
![WhatsApp Image 2026-02-11 at 4 07 19 PM](https://github.com/user-attachments/assets/4ae90c96-e483-4f30-86ee-fc1033283f6f)

# RESULT:
Thus, the program to generate pseudorandom numbers using the C standard library was successfully implemented and executed. 
