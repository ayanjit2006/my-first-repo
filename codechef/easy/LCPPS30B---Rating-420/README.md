# LCPPS30B - Rating 420

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

Write a program to find the area and perimeter of square whose side length is `4.5`. On the first line, print square's area and on the second line, its perimeter.

 **Note:** 
Area of a Square = side × side
and, Perimeter = 4 x side

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-25T01:17:21.881Z  

```c_cpp
#include <iostream>

using namespace std;

int main() {
    double s = 4.5;
    double area = s * s;
    double perimeter = 4 * s;
    cout << area << endl;
    cout << perimeter;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPS30B)