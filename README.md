# 1122Try

C++ 之父 Bjarne Stroustrup 曾言：『放鬆讓自己進入語言的世界，旅程開始時，不要認為您會使用所有的特色，也不用企圖一開始就使用所有的特色。』

Lets have a big smil & start on a quick, simple, easy hand-on journey in C++!

to know the structure of this little side project of C++

IDE using VSCode (Apple Xcode is alternative, due to C++ & Clang installed in its IDE)

# Project Stucture 

    .vscode __
             |
             |__  1122.c
             |
             |__ c_cpp_properties.json
             |
             |__ launch.json
             |
             |__ setting.json
             |
             |__ tasks.json
             
install Plugins

* Intellisense

* Clang Command Adapter

* Code Runner

options : 

Clang

LLVM

# Code

    // C++ project

    #include <stdio.h>
    #include <stdlib.h>
    #include <string.h>

    void funcQ(){

        int iA[] = {1, 2, 3, 4, 5};
        char sA[] = "QUEEN";
        // char sA[6] = {'Q', 'U', 'E', 'E', 'N', '\0'};

    }

    int main(){
    
        funcQ();
        return 0;
        
    }

# Code Runner

    [Running] cd "~/Desktop/1125.vscode/" && gcc 1122.c -o 1122 && "~/Desktop/1125.vscode/"1122

    [Done] exited with code=0 in 0.553 seconds


