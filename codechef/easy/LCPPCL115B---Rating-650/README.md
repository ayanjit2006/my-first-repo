# LCPPCL115B - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Printing numbers 10 - 0

Listen

Let us change the problem a bit.

### Task

Write a program to print numbers from $10$ to $0$ on separate lines:

- Think of where the loop should start from, declare a variable a and initialise it to that value.
- Use the while syntax to create a loop, Think of what condition would stop the loop when the iterator reaches its end. Think of how to adjust the value of the iterator within each iteration. Would it be incremented or decremented?
### Expected Output:

```
10
9
8
7
6
5
4
3
2
1
0

```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-30T05:34:48.021Z  

```c_cpp
#include <bits/stdc++.h>

using namespace std;

int main() {
    // Solution as follows
    int i = 10;
    while (i >= 0) {
        cout << i << endl;
        i--;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL115B)