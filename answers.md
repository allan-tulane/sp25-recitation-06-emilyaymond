# CMPS 2200 Recitation 06
## Answers

**Name:** Emily Aymond


Place all written answers from `recitation-06.md` here for easier grading.



- **2)** W(n) = W(n-1) + W(n-2) + O(1)
- Base: n=1: W(n) = O(2^n-1) + O(2^n-2) + O(1) = O(2^n)

- **3)** S(n-1) + O(1) = O(n)

- **4)** In the counts list, it continuously repeats the sequence and rewrites values that it already calculated before finally calculating the correct sequence.

- **6)** It will be called a maximum amount of n times because it goes through once for every value. This makes the work and span O(n).

- **8)** It will be read for a maximum amount of n-2 times. This means that the work and span of fib_bottom_up is O(n).
