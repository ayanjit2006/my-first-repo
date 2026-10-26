# CPPCLOP12 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Coding Problem

Listen

You are given a character in the variable $name$.
There is a special rule in Chef town - You will get special treatment if your name is `C` or `A`.

Output the following:

- 1 if the name is A or C
- 0 otherwise

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-26T13:10:38.770Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    char name = 'D';
    cout<<(name =='C' || name == 'A');
}

```

---

[View on CodeChef](https://www.codechef.com/problems/CPPCLOP12)