# LCPPCL115C - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Odd numbers

Listen

### Task

Write a program to print odd numbers between $10$ to $20$ on separate lines:

- Think of where the loop should start from, declare a variable a and initialise it to that value.
- Use the while syntax to create a loop, Think of what condition would stop the loop when the iterator reaches its end. Think of how to adjust the value of the iterator within each iteration. Would it be incremented or decremented? By what value should it be incremented or decremented?
#### Expected output:

```
11
13
15
17
19

```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-30T05:35:32.433Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int i = 11;
    while (i < 20) {
        cout << i << endl;
        i += 2;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL115C)