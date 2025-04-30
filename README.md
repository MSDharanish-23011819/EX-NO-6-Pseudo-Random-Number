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
A = 1664525
C = 1013904223
M = 2 ** 32 

def lcg(seed):
    return (A * seed + C) % M

print("  ***Pseudorandom number generator***\n")

seed = int(input("Enter the seed value: "))
n = int(input("Enter how many random numbers to generate: "))

print("Random numbers:")
for _ in range(n):
    seed = lcg(seed)
    print(seed)
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/bfac61c0-bcbf-47e0-9912-f6fe9ce9347d)

# RESULT:
The implementation of Pseudorandom Number Generation using Standard library is successful.
