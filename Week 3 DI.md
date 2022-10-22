# 10/12 Discussion

## Basic formulas

![](assets/20221021170209.jpg)

## X86 Basics

![](assets/20221021170431.jpg)

## RBP, RSP

![](assets/20221021170923.jpg)

## Arithmetic

![](assets/20221021171017.jpg)

## Cache

![](assets/20221021171133.jpg)

## Fully Associative Cache

![](assets/20221021171236.jpg)

## Misses

Compulsory (or cold-start) misses

- first access to the data.

Capacity misses

- we missed only because the cache isn’t big enough.
- Defn: The address has already been requested AND a fully associative cache of the same size
  would also experience a miss

Conflict misses

- we missed because of the indexing scheme/addresses caused one block to evict another
  earlier than one might hope
- Defn: The address has already been requested AND a fully associative cache of the same size
  would experience a hit
