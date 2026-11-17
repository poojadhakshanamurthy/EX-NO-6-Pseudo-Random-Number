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
{
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Generated Random Numbers:\n");

    for(i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```
# OUTPUT:
<img width="1524" height="742" alt="Screenshot 2026-11-17 195839" src="https://github.com/user-attachments/assets/355c507e-6ffb-4bb6-a2cf-54738c9eaeb2" />

# RESULT:
The implementation of Pseudorandom Number Generation using Standard library is successful.
