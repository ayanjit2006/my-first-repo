# LCPP30 - Rating 650

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

Declare a variable  **"temperature"**  and initialize it with a value of 25.5 (in Celsius) and print it in Celsius and Kelvin (add 273 to the temperature in Celsius).

[ **Note:**  Print the output in exactly the same format as given below. There is single space around hyphen(-)]

### Output Format

Celsius - 25.5
Kelvin - 298.5

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-25T01:16:29.469Z  

```c_cpp
#include <iostream>

using namespace std;

int main() {
    float temperature = 25.5;
    cout << "Celsius - " << temperature << endl;
    cout << "Kelvin - " << temperature + 273;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPP30)