![](https://github.com/mary060196/CISC3160_Project/blob/master/The%20Toy%20Language.png?raw=true)
# <p align="center">The Toy Language Interpreter Project: Picat Version</p>
## Details

**Author**: Miriam Briskman

**Supervised by**: Professor Neng-Fa Zhou

**Course**: CISC 3160, "Programming Languages", of CUNY Brooklyn College

**Semester**: Fall 2019 (and beyond!)

**Used Language:** Picat

**Assignment's Description**: http://www.sci.brooklyn.cuny.edu/~zhou/teaching/cis3160/project.html
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
- Try the interpreter on `errors1.txt`, `errors2.txt`, `test.txt` and `test2.txt` found in this repository. 
  - The files `errors1.txt` :
  
    ```
    ampersand = &;
    y++;
    6 = 6;
    w z = 3;
    anotherVar = 7 8;
    num = 15*8+(16+ -4*9));
    c = 0-8;;
    res = 2+2*;
    g;
    = 14;
    x = ((5+6);
    cat = 5(2+3);
    _ == 0;
    temp = 2+*5;
    e = (3-);
    y = t;
    y = 4+9
    ```
    and `errors2.txt` :
    
    ```
    x
    ```
    test for 17 different syntactic errors and 1 semantic error (uninitialized variables). 
  - The files `test.txt`:
  
    ```
    _FOO = 9+9*7--5*7--8+9;
    bar007 = 9+0-5--_FOO;
    bla_bla = ---0*7+8+8+8;
    y=1+2+3+4+5;
    x=y;
    z = x-y-y+y-x;
    p=1;
    q=2;
    s= -p*-q+p*q*p;
    r=p*-++-+-p*(p+p+p);
    t=2*p+5*5+8+8;
    a=+t--t+t*(p+(q-p*-q));
    b=-(a)-(a);
    wow = 1;
    wow = wow + 1;
    sue = (x+y)++((x-y)+2)*-(p-3);
    bill = (((a)))+-((1))*(((2)));
    ```
    and `test2.txt`:
    
    ```
    a = 7*7*7;
    row = +6+6+---4*0+5-9*1;
    y
    = 5+6;
    d = 7*7*7+6+6+---4*0+5-9*1--3--3;
    e = 5--3--3;
    x = d+e;
    wow = (7*7*7+6+6+---0*4+5-9*1--3--3)*2;
    rare = --2+3--3++9*1*2*1---4---2--1---3+12-7+5-21;
    ```
    contain _no_ errors. Use them to see how the interpreter successfully prints the values of all the variables.
<hr>

**Thank you for Reading!** Miriam Briskman
