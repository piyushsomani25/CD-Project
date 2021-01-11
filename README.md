# CD-Project
## Hardware Requirements 
Usage of CPU, RAM, and storage space can vary significantly based on user behavior. 
These hardware recommendations are based on my work on the project. 
● A Computer System 

● Ethernet connection (LAN) OR a wireless adapter (Wi-Fi) 

● Processor: Minimum 1 GHz 

● Sufficient memory to install required libraries Software Requirements 


## Software requirements 
● GCC Compiler (for execution of C/C++ scripts) 

● Flex Compiler (for execution of lex scripts) 

● Bison Compiler (for execution of yacc scripts) 


### File Structure:
|-- app

|-- appx.exe

|-- input.txt

|-- lex.yy.c

|-- main.l

|-- main.tab.c

|-- main.tab.h

|-- main.y

|-- output1.txt

`-- programrun.bat


## Execution Steps:
#### Run The program in terminal

flex main.l

bison -d main.y

gcc lex.yy.c main.tab.c -o app -lm

./app

### Procedure

1.The code is divided into two part flex file (.l) and bison file (.y) .

2 Input Expression check the lex (.y) file and if the expression satisfies the rule 
Then it checks the CFG in the bison file.

3.Its a bottom up parser and the parser construct the parse tree .firstly ,matches
the leaves node with the rules and if the CFG matches then it gradually goes to
the root .

## Developer Information 
Name: Piyush Somani 

USN: 1RV18IS030

Institute: R. V. College of Engineering 

Instructor: Prof B. K. Srinivas

