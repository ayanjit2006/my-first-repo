# LOOP8V2VE

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-01T13:16:14.409Z  

```c_cpp
#include <bits/stdc++.h>

using namespace std;

int main() {

    int n;
    cin  >> n;
    for(int i = 0; i <= 12; i = i + 1) {
    if(i == n) {
            continue;
        }
        cout << i << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LOOP8V2VE)