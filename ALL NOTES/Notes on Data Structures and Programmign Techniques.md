[Link to the notes online](http://cs.yale.edu/homes/aspnes/classes/223/notes.html#compilationTools)

### GDB
- Compile with -g3 to show variable names and source lines in gdb

### Versions of C
 - **K&R C** The 1978 version
 - **Ansi C** from 1998
 - **C99** from 1999, added some features from C++ and new features for high performance numeric computing
 - **C11** from 2011 relaxed some requirements from C99 and added some new features
 - Many compilers disregard C99 and C11, and so Ansi C is the safest bet to target
 - **GNU C** is gnu's specific dialect which is basically Ansi C with some extra features
 - For maximum portability, use `gcc -ansi -pedantic` to target strict Ansi C

### Compiler Flags
- **-E** to show the output of the preprocessor



