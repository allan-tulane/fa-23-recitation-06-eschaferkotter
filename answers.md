# CMPS 2200 Recitation 06
## Answers

**Name:**_________________________
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
- W(n-1) + W(n-2) + O(1) = O(2^n)

- **3)**
- S(n-1) + O(1) = O(n)
- **4)**
- The amount of calls is equal to the fibonacci sequence itself considering that to calculate any fib_recursive(n) it has to make calls to fib_recursive(n-1) and fib_recursive(n-2)
- **6)**
- The maximum number of times it will be called is i times as it stores the results, and later calls will just return what is stored. Max work is O(n) and span is also O(n)
- **8)**
- The maximum amount of times Fi is read is i times. The work and span are still O(n), comparable to top down.