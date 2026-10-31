# PPSC85 - Rating 550

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Sum of N Integers

Listen

Chef was given an integer input N.

He wants to write a code using `while` loops to output the sum of all integers from 1 to $N$.
Help him complete the code by filling in the blanks.

### Sample 1:
Input
Output

```
5
```

```
15
```

### Sample 2:
Input
Output

```
10
```

```
55
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-31T15:21:56.982Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	int n;
	cin >> n;
	int sum = 0;
	int i = 1;
	while (i <=n){
	    sum = sum + i;
	    i++;
	    
	}
	cout << sum << endl;
}


```

---

[View on CodeChef](https://www.codechef.com/problems/PPSC85)