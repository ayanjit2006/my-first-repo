# CND3V2

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### If Statement

Listen

An `"if statement"` is written by using the `'if'` keyword.

### Task

Write a program which does the following

- Take input for two integer variables a & b
- Output "Coding is Fun!" to the console if a is greater than b.
### Sample 1:
Input
Output

```
25
20
```

```
Coding is Fun!
```

### Sample 2:
Input
Output

```
20
20
```

```
 
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-27T02:38:37.638Z  

```c_cpp

#include <bits/stdc++.h>
using namespace std;

int main() {
    int a;
    int b;
   cin >> a;
    cin >> b;
    if ( a>b ) {
        cout << "Coding is Fun!";
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CND3V2)