# LCPPAS39 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Identify the errors

Identify and rectify the errors in the code provided to get the desired output.

### Sample 1:
Input
Output

```

```

```
Coding Chef
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-26T01:59:45.113Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    string one = "Coding"; // Use double qoutes for strings
    string two = "Chaf";
    two[2] = 'e'; // third character is at index 2
    cout << one + " " + two; // missing semicolon
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS39)