# LCPPCL306 - Rating 850

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Multiple choice question

What does the following code do?

```
int x = 10;
int *p = &x;
 *p =* p + 5;

```

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-03T03:56:20.579Z  

```cpp
#include <iostream>
using namespace std;

int main() {
    int numbers[] = {10, 20, 30, 40, 50};
    int *ptr = numbers; // Pointer to the first element

    for (int i = 0; i < 5; i++) {
        cout << *ptr << endl;
        ptr++; // Move the pointer to the next element
    }

    return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL306)