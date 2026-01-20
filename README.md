# String-Append-in-Cpp
This repository contains a simple C++ program that demonstrates the use of the append() function to add text to an existing string.  The program initializes a string with multiple words and then appends another word to it using the append() method of the C++ string class.
# String Append in C++

This repository contains a simple C++ program that demonstrates how to **append text to a string using the `append()` function**.

## 📌 Program Description
The program initializes a string with multiple words and then appends another word to the string. This example helps beginners understand how string concatenation works in C++ using the standard string library.

## 🧠 Concepts Covered
- C++ string handling
- `append()` function
- String concatenation
- Basic input/output operations

## 💻 Source Code
```cpp
#include<iostream>
using namespace std;

int main(){
    string s = "apple Bananna cherry";
    s.append(" mango");
    cout << s << endl;
    return 0;
}
