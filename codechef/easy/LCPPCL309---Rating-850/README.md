# LCPPCL309 - Rating 850

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### MCQ - 2

Which of the following is the correct version of `swap()` function to swap two numbers using Pointers.?

 **Option 1:** 

```
void swap(int  *ptr1, int* ptr2) {
    int temp = *ptr1;
     *ptr1 =* ptr2;
    *ptr2 = temp;
}

```

 **Option 2:** 

```
void swap(int  *ptr1, int* ptr2) {
    int temp = *ptr1;
     *ptr1 =* ptr2;
    *ptr1 = temp;
}

```

 **Option 3:** 

```
void swap(int  *ptr1, int* ptr2) {
    int temp = *ptr1;
    *ptr2 = temp;
}

```

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-03T03:57:15.100Z  

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

[View on CodeChef](https://www.codechef.com/problems/LCPPCL309)