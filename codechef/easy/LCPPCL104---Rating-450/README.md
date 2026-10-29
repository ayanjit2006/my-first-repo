# LCPPCL104 - Rating 450

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Debug the code - 6

Listen

There are N bikes and M cars on the road.

- Each bike has 2 tyres.
- Each car has 4 tyres. Find the total number of tyres on the road.
### Input Format
- The first and only line of each test case contains two integers N,M.
### Output Format
- For each test case, output in a single line, the total number of tyres on the road.
### Constraints
- 0 ≤ N, M ≤ 100.
### Sample 1:
Input
Output

```
2 1
```

```
8
```

### Sample 2:
Input
Output

```
3 0
```

```
6
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-29T04:35:27.483Z  

```c_cpp
#include <iostream>

using namespace std;

int main() {
    int N, M;
    cin >> N >> M;
    cout << (N * 2 + M * 4) << endl; // wrong previous operations

}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL104)