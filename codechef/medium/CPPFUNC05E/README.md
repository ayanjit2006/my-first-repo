# CPPFUNC05E

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-19T03:15:48.866Z  

```c_cpp
#include <iostream>
using namespace std;

void computeValue(int a, int b) {
    // Solution as follows
    int c = a * a + 2 * a * b + b * b;
    int d = a + b;
    cout << c << endl;
    cout << d << endl;
}

int main() {
    int t = 3;
    for (int i = 0; i < t; i++) {
        int A, B;
        cin >> A >> B;
        computeValue(A, B);
    }
    
}

```

---

[View on CodeChef](https://www.codechef.com/problems/CPPFUNC05E)