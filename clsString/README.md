# String-Lib-cpp
# clsString

A C++ string manipulation library featuring a custom `clsString` class.  
Created as a personal project for learning and utility purposes.

---------------------------------------------------

## 🔧 Features

- Custom `clsString` class
- Editing strings (append, insert, remove, etc.)
- Comparing strings
- Formatting and cleaning up strings (e.g., trimming)
- Easy to use, lightweight, and beginner-friendly
- No external dependencies (uses only standard C++)
---------------------------------------------------
## Example Usage:

#include "clsString.h"
#include <vector>


 int main() 
 
 {
    clsString str("Hello World! Hello everyone.");
   
    str.ReplaceWord("Hello", "Hi");
    
    int count = str.CountWords();
   
    std::vector<std::string> words = str.Split(' '); 
  
    return 0;}
     
--------------------------------------------------
## Library Status:

The library is completed but may have some new updates in the future.

--------------------------------------------------

## Author:

Created by Mohammed Alhamad (W0mmd).

