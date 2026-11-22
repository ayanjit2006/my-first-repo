# GSCV215

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Debug this code - Why is this code incorrect

Listen

So as you solve programming problems - you will need to debug and find errors in your own code.

### Task

You are given a program which does the following

- Accepts the count of test cases - t - in the 1st line The only line of each test case consists of an integer N
- For each test case, output to the console the value that is double the integer N

Can you try and  **debug / fix**  the error in the given program?

### Sample 1:
Input
Output

```
3
1
2
3
```

```
2
4
6
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-22T03:13:34.892Z  

```c_cpp
// Solution as follows
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int t;
    cin >> t;
    while (t--)
    // without '{' you'll get a compilation error
    {
        //N should be declared as an 'int'
        int N;
        cin >> N;
        cout << 2 * N << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/GSCV215)