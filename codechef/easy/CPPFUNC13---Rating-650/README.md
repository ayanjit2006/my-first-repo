# CPPFUNC13 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Coding problem-2

Listen

Given $n$ ($n$ is  **even**), determine the number of  **black cells**  in an $n \times n$ chessboard.
Solve the problem.

### Input Format

The only line of the input contains a single integer $n$.

### Output Format

Output the number of black cells in an $n \times n$ chessboard.

### Constraints
- $2 \leq n \leq 100$
- $n$ is even
### Sample 1:
Input
Output

```
8
```

```
32
```

### Explanation:

There are $32$ black cells and $32$ white cells in an $8 \times 8$ chessboard. So the answer is $32$.

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-03T03:44:37.720Z  

```c_cpp
#include <iostream>

using namespace std;

int square(int t) {
    int value1 = t * t;
    return value1;
}

int half(int i) {
    int value2 = i / 2;
    return value2;
}

int main() {
    int n;
    cin >> n;
    
    int result1 = square(n);
    int result2 = half(result1);
    
    cout << result2 << endl;
    
    
}

```

---

[View on CodeChef](https://www.codechef.com/problems/CPPFUNC13)