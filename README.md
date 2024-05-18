# CDucky
simulate Rubber Ducky concept in c++

## Install

````

git clone https://github.com/ghalyd/CDucky.git

````



## Usage


````C++

#include "include/CDucky.h"

using namespace std;

int main(){

    GUIR();
    
    Sleep(500);
    PressKeys("powershell");
    Sleep(500);
    ReturnKey();
    Sleep(500);
    PressKeys("echo 'Hello World From HopeDucky!'");
    Sleep(500);
    ReturnKey();
    

    return 0x0;
}



````
