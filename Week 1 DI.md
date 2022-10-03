## Problem 1: Onlined ordering website

1. If there are 2 servers, for each server, it takes 1 ms to process

- latency (in ms): 1 ms
- throughput (in order/second):
  `2*1/(1*10^{-3}) = 2000`

2. If there is 1 server, takes 5 ms to process

- latency: 5 ms
- throughput (in order/second):
  `1*1/(5*10^{-3}) = 200`

> x is n times faster than Y
>
> ### speed up = n = `latency(Y)/latency(X) = throughput(X)/throughput(Y)`

## Problem 2

A laptop takes 4 hours to compress a video, new laptop 10 minutes

```
speed up = latency(old)/latency(new)
         = 4*60/10
         = 24
```

> ### `Execution time = # instruction * CPI * Cycle Time`

## Problem 3

10 billion instructions, CPI = 2, Clock frequency = 4 GHZ

> `ET = 10*10^9*2*1/(4*10^9) = 5`

## Problem 4

50 billion instructions

- 10 Billion branch instruction --> CPI = 4
- 15 billion load instruction --> CPI = 2
- 5 billion sto instruction --> CPI = 3

f = 4 GHZ, CPI = 1

> ```
> (10*10^9*4)*1/(4*10^9) + (15*10^9) *2 * 1/(4*10^9) + 5*10^9*3*1/(4*10^9) + 20*10^9 * 1 * 1/(4*10^9)
> = (40+30+15+20)*1/4 = 105/4 = 26.25 second
> ```

## Problem 5

5 billion instructions
Speed up 70% of Execution time by a factor of 2, overall speed up?

> ![](assets/20220928160846.jpg)
>
> ```
> Speedup = 1/[(0.7/2) + (1-0.7)] = 1/(0.35+0.3) = 1/0.65 = 1.54
> ```
