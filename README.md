Reading notes of Computer Organization and Design - The Hardware/Software Interface (Arm Edition)

# Chapter 1.6

## Response time

Also called execution time.

- The total time required for the computer to complete a task, including disk accesses, memory accesses, I/O activities, operating system overhead, CPU execution time, and so on.

## throughput

Also called bandwidth

- Another measure of performance, number of tasks completed per unit time

## Performance and Execution time

To maximize performance, we want to
minimize response time or execution time for some task. Thus, we can relate
performance and execution time for a computer X:

![](assets/20220926233549.jpg)
![](assets/20220926233614.jpg)

> Example, if A runs a program in 10 seconds, B runs the same program in 15 seconds, how much faster is A than B?
>
> Performance_A / Performance_B = Time_B / Time_A = 15/10 = 1.5

## CPU time

- user CPU time
  - The actual CPU time spent in a program itself
- system CPU time
  - The CPU time spent in the operating system performing tasks on behalf of the program

## CPU Performance

refer to the user CPU time

## Clock cycle

also called tick, clock tick, clock period, clock, or cycle

- The time for one clock period, usually of the process clock, which runs at a constant rate.

## Clock period

The length of each clock cycle

## CPU Performance and its factors

![](assets/20220927002611.jpg)

## Instruction performance

![](assets/20220927064707.jpg)

## Clock cycles per instruction (CPI)

Average number of clock cycles per instruction for a program or program fragment

> Example:
> Suppose we have two implementations of the same instruction set architecture.
> Computer A has a clock cycle time of 250 ps and a CPI of 2.0 for some program,
> and computer B has a clock cycle time of 500 ps and a CPI of 1.2 for the same
> program. Which computer is faster for this program and by how much?

![](assets/20220927064949.jpg)

## The Classic CPU Performance Equation

## Instruction count

The number of instructions executed by the program

## New formula

![](assets/20220927065141.jpg)
These formulas are particularly useful because they separate the three key factors
that affect performance. We can use these formulas to compare two differen
implementations or to evaluate a design alternative if we know its impact on these
three parameters.

> Example:
> ![](assets/20220927065851.jpg)

## Instruction Mix

A measure of the dynamic frequency of instructios across one or many programs

## Understanding program performance

The performance of a program depends on the algorithm, the language, the
compiler, the architecture, and the actual hardware. The following table summarizes
how these components affect the factors in the CPU performance equation
![](assets/20220927065804.jpg)

![](assets/20220927070035.jpg)

> Choose B
