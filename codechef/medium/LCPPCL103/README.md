# LCPPCL103

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-29T04:34:48.283Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    int a,b,c,d;
    cin>>a>>b>>c>>d;
    float p = a - c; // price of first tv after discount was wrong
    float q = b - d; // price of second tv after discount was wrong
    if(p<q){
       cout<<"First"<<endl;
    }
    else if(p>q){
       cout<<"Second"<<endl;
    }
    else if(p==q) {
       cout<<"Any"<<endl;
    }
	
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL103)