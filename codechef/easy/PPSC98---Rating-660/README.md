# PPSC98 - Rating 660

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Nested loops continued

Listen

Ok - try out a problem yourself.

### Task

Given an integer $N$ - create a square pattern of side $N$.

Check the sample output given below for $N$ = 4.

### Sample 1:
Input
Output

```
4
```

```
 **   ** 
 **   ** 
 **   ** 
 **   ** 
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-01T13:24:46.106Z  

```c_cpp
#include<bits/stdc++.h>
using namespace std;


int main() {
    int n;
    cin >> n;
    for(int i = 0; i < n; i++) {
        for(int j = 0; j < n; j++)
        
        cout << "* ";
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/PPSC98)