# LCPPCL304CE

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-19T03:46:34.250Z  

```c_cpp
#include <iostream>
using namespace std;

void printValue(int *ptr) {
    if (ptr != nullptr) { // Check if the pointer is not null
        cout << "Value: " << *ptr << endl;
    } else {
        cout << "Pointer is null" << endl;
    }
}

int main() {
    int *number = nullptr; // Pointer is null initially
    printValue(number); // This should print the value pointed to by the pointer
    return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL304CE)