# CPPFUNC01VE

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Functions in Cpp

Listen

Let us solve a simple problem to help us understand the importance of functions.

### Task

Your are given 3 lines of input.

- Each line consists of 2 space separated integers - $A$ and $B$

For each input - you need to compute and output the following on separate lines

- $A^2 + 2 *A* B + B^2$
- $A + B$

Check the sample output below to understand this problem statement better.

### Sample 1:
Input
Output

```
3 5
2 7
4 1
```

```
64
8
81
9
25
5
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-01T13:35:33.368Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {

        int A, B;
        cin >> A >> B;
        
        int C = A * A + 2 * A * B + B * B;
        int D = A + B;
        
        cout << C << endl;
        cout << D << endl;

        cin >> A >> B;
        
        C = A * A + 2 * A * B + B * B;
        D = A + B;
        
        cout << C << endl;
        cout << D << endl;
        cin >> A >> B;
        
        C = A * A + 2 * A * B + B * B;
        D = A + B;
        
        cout << C << endl;
        cout << D << endl;
    
    
}

```

---

[View on CodeChef](https://www.codechef.com/problems/CPPFUNC01VE)