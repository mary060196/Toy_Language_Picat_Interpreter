![](https://github.com/mary060196/CISC3160_Project/blob/master/The%20Toy%20Language.png?raw=true)
<h1 align="center">The Toy Language Interpreter Project: Picat Version 2.0</h1>

## Details

**Author**: Miriam Briskman

**Supervised by**: Professor Neng-Fa Zhou

**Course**: CISC 3160, "Programming Languages", of CUNY Brooklyn College

**Semester**: Fall 2019 (and beyond!)

**Used Language**: Picat

**Assignment's Description**: http://www.sci.brooklyn.cuny.edu/~zhou/teaching/cis3160/project.html

**What's New in Version 2.0**:
- Most loops, `if` conditionals, and `:=` assignments replaced by recursive procedures.
- Optional goals (conditions) used to combine similar instructions.
- Enhanced rror recovery mode displays several semantic errors per statement.
- Uncompromised running time and efficiency.
- Overall code length shortened by 53%.
- Compilation time reduced by 32%.
- Additional testing files added (see **Examples** below.)

__Statistical details of the performed changes__:
- Length (only in lines of code, without comments and blank lines) of individual modules:

  - `toylang.pi` - from 54 to 50 - a reduction of 7,4074074074%.

  - `parser.pi` - from 411 to 206 - a reduction of 49,8783454988%.

  - `semantics.pi` - from 294 to 99 - a reduction of 66,3265306122%.

  - `tokenizer.pi` - from 57 to 28 - a reduction of 50,8771929825%.

- Length of the Entire Program:

  - From 816 to 383 - a reduction of 53,0637254902%.

- Compilation time of the program (in milliseconds):

  - From 299 to 202 - a reduction of 32,4414715719%.

- Total running time of the program on example programs (in milliseconds):

  - `test.txt` - from 8 to 8 - no change.

  - `errors1.txt` - from 133 to 128 - a reduction of 3,7593984962%.

## Getting Started
- Download the Picat processor to your device from http://picat-lang.org/download.html
- Add the address of the directory where the Picat folder resides to the environment variable PATH.
- Save all the files from this repository into a single folder on your computer.
- Create a text file, say `myProg.txt`, with a program that you want to interpret in that same folder.
- Using a command-line processor:
  - Change the current directory (cd) to where the files were downloaded.
  - Type:

    `picat toylang myProg`
    
    or type
    
    `picat toylang`

    and follow the instructions to enter the name of the textfile to interpret.

## Examples
- See program examples at http://www.sci.brooklyn.cuny.edu/~zhou/teaching/cis3160/project.html.
- Try the interpreter on `errors1.txt`, `errors2.txt`, `errors3.txt`, `errors4.txt`, `test.txt`, `test2.txt`, `test3.txt`, and `test4.txt` found in this repository. 
- The files `errors1.txt`, `errors2.txt`, `errors3.txt`, and `errors4.txt` test for 17 different syntactic errors and 1 semantic error (uninitialized variables). 
- The files `test.txt`, `test2.txt`, `test3.txt`, and `test4.txt` contain _no_ errors. Use them to see how the interpreter successfully prints the values of all the variables.
<hr>

**Thank you for Reading!** Miriam Briskman
