```c++
#include <stdio.h>
#include<iostream>
using namespace std;
struct p{
    char y; // -> 1
    int x;  // -> 4
    double d; // -> 8
};
// 1+4+8=13 -> 16 (inc order)
// 1+4+4=9 -> 12

// 1+4+1 -> 4+4+..+1 = 9 = 12
// 1+1+4+1 -> 4+4+..+1 = 12

// 1+8+1+8 =8+8+8+8 =32
// 1+8+4+1 =8+8+4+1=21 -> 24

// 1+4+8+4+1 = 4+4+8+4+1=21 ->24

// 1+4+1+8 = 4+4+8+8 ->24

// 1+4+1+8 +1+1+1+1 =28 -> 32

int main(){
    cout<<sizeof(p);
}

```
