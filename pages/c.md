# C

C is widely used programming language that was orginally invented in Bell Labs in the 1970s. 
As a low level programming language, that is often used in high-performance and embedded system.
<img style="float: right; width:30%; height:50%; object-fit:contain;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/The_C_Programming_Language_logo.svg/800px-The_C_Programming_Language_logo.svg.png">

# Nerd stuff
C is statically typed imperative language. Unlike more modern language like C++ and Java, it lacks modern object oriented programming features like classes and inheritance. 

C is a compiled language. 
The C preprocessor allows programmers to write predefined marcos, and allows some metaprogramming abillity.

C doesn't do garbage collection, memory mangament must be handled manually. Programmers must be caution of memory leaks and segfaults.

Most data structures must be built yourself.

# Ecosystem

To compile a program, one must have a compiler. Popular compilers include Clang and GCC.

If you are using Linux (Ubuntu or any distrubtion using apt package manager) you can install GCC by running:
```
sudo apt install build-essential
```
in your commmand line.

You can compile programs by running
```
gcc -o outputfilename your_code.c
```

For more larger programs that have more complicated compliation process, make files are often used to automate it. 

Some popular libaries include.

Open SSL for secure networking
GSL Math and numerical function.
SDL for graphics.

# Examples
```c
#include <stdio.h>

// We can write comments by starting a with double slashes
// everything after doubles slashes is igroned

int main() {
   printf("Hello World!");
   return 0; // we return 0 to indicate the program has executed without error
}
```

# Stats

|           | Used by | Loved*| Hated*|
|-----------| ------- |--     | --    |
| C      | 19.27%    | 39.68% | 60.32% |

\* Out of the developer who currently work with this language, how many (wish/do not wish) to continue working with this language. 

Stats from https://survey.stackoverflow.co/2022/#technology-most-popular-technologies