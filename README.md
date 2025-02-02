# Rainbow Animation Library
ranim-lib (Rainbow Animation Library) - a library for animating text into a rainbow in C 

## 📎Documentation
> Works on Windows, Linux, it is possible to add it to c++ code due to the compatibility of c with c++

* Code Example:
```
#include <stdio.h>
#include "./ranim-lib/src/ranim.h"

int main(){
    ranimln("Hello World =)");
    return 0;
}

```
* Compilation:
```
gcc main.c ./ranim-lib/src/ranim.c -o name-program -lm
```
## 📝 To Do 
* [ ] - Add the ability to many arguments in the ranimln function
* [ ] - Add to a Debian-like system, you can install the library using the ```sudo apt-get``` command.



## 📷Preview

![Preview](https://github.com/rediskazavr/ranim-lib/blob/main/preview.gif)

## 📌Sources
> This project appeared absolutely by accident. It is used in the [TUI-OS project](https://github.com/rediskazavr/TUI-OS), as a display of text using color animation

