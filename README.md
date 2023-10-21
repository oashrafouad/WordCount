# WordCount
Flex program that reads a text file and calculates the number of words and characters in each word in that file. This is an assignment to the Compiler Construction course in uni.

# How to Run
This program compiles using `flex` and `g++`

1. Clone the repo and modify the `in.txt` file to your liking. The program will count the words and characters in this file.
2. Open the cloned repo's directory in terminal
3. Run `flex Assignment1.l` to compile the program into C code
4. Run `g++ lex.yy.c` to compile the C code into an executable
5. Run the executable
   - Run `a.exe` if you're on Windows
   - Run `./a.out` if you're on Linux or Mac
