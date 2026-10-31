# PPSC94 - Rating 460

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Sum of Even Integers

Listen

You are given an integer $N$.

You need to output the sum of all even integers from 1 to $N$.
Check the sample output given below.

### Sample 1:
Input
Output

```
5
```

```
6
```

### Sample 2:
Input
Output

```
10
```

```
30
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-31T15:32:44.749Z  

```c_cpp
#include <bits/stdc++.h>

using namespace std;

int main() {
    int n;
    cin >> n;
    int sum = 0;
    for (int i = 2; i <= n; i+=2) {
        sum += i;
    }
    cout << sum << endl;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/PPSC94)