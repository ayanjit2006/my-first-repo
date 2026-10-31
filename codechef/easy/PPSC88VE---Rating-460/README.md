# PPSC88VE - Rating 460

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-31T15:27:59.960Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    int count = 0;
    while (n > 0) {
        count++;
        n = n / 10;
    }
    cout << count << endl;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/PPSC88VE)