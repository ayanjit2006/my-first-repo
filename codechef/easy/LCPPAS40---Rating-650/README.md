# LCPPAS40 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Print the length

Write a program to print the length of each word of the sentence given below as well as the length of the whole sentence.
 **"Coding on CodeChef"** 

[ **Note:**  Don't forget to print the outputs in same format as given below.]

### Sample 1:
Input
Output

```

```

```
Coding - 6  
on - 2  
CodeChef - 8  
Coding on CodeChef - 18  
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-26T02:04:00.477Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	string one = "Coding";
	string two = "on";
	string three = "CodeChef";
	string four = one + " " + two + " " + three;
	cout << one + " - " << one.length() << endl;
	cout << two + " - " << two.length() << endl;
	cout << three + " - " << three.length() << endl;
	cout << four + " - " << four.length();
	return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPAS40)