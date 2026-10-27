# SYNMCQ22 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Multiple Choice Question

What will be the output of this code, if the a = 5 and b = 9 based on user input?

```
#include <bits/stdc++.h>
using namespace std;

int main() 
{
    int a, b;
    cin >> a >> b;
    cout << a << b << a + b;
    
    return 0;
}

```

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-27T02:15:02.897Z  

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    
    int a, b;
    int sum;
    int diff;
    cin>>a;
    cin>>b;
    sum = a+b;
    diff = a-b;
    
     
    cout << "Sum is: " << sum << endl;
    cout << "Difference is: "<< diff << endl;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/SYNMCQ22)