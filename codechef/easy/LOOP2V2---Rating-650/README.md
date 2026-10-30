# LOOP2V2 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-30T05:37:27.296Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n = 128;
    //Initialization: set i to the starting value
    int i = 2;
    //Condition: keep repeating till less than equal to n
    while (i <= n) {
        //Output i(current number)
        cout << i << endl;
        // Update Statement: At each iteration multiply i(current number) by 2
        i *= 2;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LOOP2V2)