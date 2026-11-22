# LCPPCL313E - Rating 970

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-22T02:55:51.954Z  

```c_cpp
#include <iostream>
using namespace std;

void increment(int *x) {
    (*x)++;
    cout << "new value during function: " << *x << endl;
}

int main() {
    int num = 5;
    increment(&num);
    cout << "num after function call: " << num << endl; // Output: num after function call: 6
    return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL313E)