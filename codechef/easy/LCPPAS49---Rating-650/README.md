# LCPPAS49 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Area of circle

Write a program that takes the radius of a circle as input and prints its area.

The formula of the area of a circle is $pi  *radius*  radius$.
Take the value of pi to be $3.14$

### Sample 1:
Input
Output

```
5
```

```
78.5
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-26T02:18:17.558Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    float radius;
    cin >> radius;
    cout << 3.14 * radius * radius << endl;

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS49)