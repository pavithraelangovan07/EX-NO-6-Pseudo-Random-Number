# EX-NO-6-Pseudo-Random-Number
## NAME:E.PAVITHRA
## REG NO:212224220072
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

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}

```
# OUTPUT:
<img width="1916" height="1150" alt="image" src="https://github.com/user-attachments/assets/ca3a42d4-0989-4ac9-841e-678f1fee0efd" />

# RESULT:
Thus, pseudorandom number generation was successfully implemented using the C standard library functions rand(), srand(), and time().
