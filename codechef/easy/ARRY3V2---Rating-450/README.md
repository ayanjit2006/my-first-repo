# ARRY3V2 - Rating 450

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Changing the elements of an Array

Listen

To change the `value` of a specific element, we can refer to the `index number`.

### Task

Write a program which does the following

- The 3rd month in the given array is incorrect
- Update the 3rd month in the given array with the correct one - "Mar"
- Once the 3rd array element is updated, output the 3rd array element to the console

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-29T16:02:36.249Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() 
{
    string mnts[4] = {"Jan", "Feb", " Dec", "Apr"};
    mnts[ 2 ] = "Mar";
    cout << mnts[2];
}

```

---

[View on CodeChef](https://www.codechef.com/problems/ARRY3V2)