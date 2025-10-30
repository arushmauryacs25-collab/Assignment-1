# Assignment-1

C Assignment (Functions and Header Files)

Files included
1. main.c        – Main program (menu to use number & array functions)
2. mylib.c       – Number-related function implementations
3. mylib.h       – Declarations for number functions
4. arraylib.c    – Array-related function implementations
5. arraylib.h    – Declarations for array functions

How to compile
Open Command Prompt or Git Bash in the project folder and run:
gcc main.c mylib.c arraylib.c -o main.exe -lm

(The -lm flag links the math library used by pow().)

How to run
After compiling, run:
main.exe
