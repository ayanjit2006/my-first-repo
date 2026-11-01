# CPPFUNC08

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-01T13:51:24.492Z  

```c_cpp
#include <iostream>
using namespace std;

// Global variable
int globalVar = 10;

void myFunction() {
    // Local variable
    int localVar = 20;

    // Accessing and printing both the global variable and local variable
    cout << localVar << endl;   // Should print 20
    cout << globalVar << endl; // Should print 10
}

int main() {
    // Calling the function
    myFunction();

    // Accessing and printing the global variable
    // cout << globalVar << endl; // Should print 10

    // Trying to access the local variable here would cause an error as it's out of scope
    // cout << localVar << endl; // Uncommenting this line would cause a compilation error

    
}

```

---

[View on CodeChef](https://www.codechef.com/problems/CPPFUNC08)