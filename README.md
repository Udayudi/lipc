# C Programming Language 

## 1. A Tutorial Introduction

### [1.1 Getting Started](https://github.com/Udayudi/lipc/tree/main/chapter_1)



>The only way to learn a new programming language is by writing programs in it. 

The first program to write is the same for all languages:
Print the words
hello, world
This is a big hurdle; to leap over it you have to be able to create the program text somewhere,
compile it successfully, load it, run it, and find out where your output went. With these
mechanical details mastered, everything else is comparatively easy. 

```
#include <stdio.h>
main()
 {
     printf("hello, world\n");
 }
``` 
Just how to run this program depends on the system you are using. As a specific example, on
the UNIX operating system you must create the program in a file whose name ends in ``.c'',
such as hello.c, then compile it with the command
 cc hello.c

