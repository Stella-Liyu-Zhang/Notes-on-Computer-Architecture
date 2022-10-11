## Amdahl's Law

You have a program with 25% integer instructions and 75% multimedia instructions. We optimized the multimedia instructions by a factor of 2. Calculate the speedup with respect to unoptimized code.

>

```
CPI_A = 2; CPI_B = 4

ET_new = (0.75*IC*CPI_B*CT)/2 + 0.25*IC*CPI_A*CT

Speedup = ET_new/ET_old =
```

> ![](assets/20220928160846.jpg) > ![](assets/20220928160928.jpg)

## X86 assembly

- Compile converts high level language to machine language

- General Purposes Registers
- Special Registers
