learning-cobol
==============

This repository was created to learn basics of COBOL language and feel some old school vintage breeze

![Grace Murray Hopper at the UNIVAC keyboard, c. 1960](https://raw.githubusercontent.com/pwittchen/learning-cobol/master/assets/Grace_Hopper_and_UNIVAC.jpg)

*Grace Murray Hopper (creator of COBOL) at the UNIVAC keyboard, c. 1960*

Preparation for Linux
---------------------

Install COBOL compiler with the following command:

```
$ sudo apt-get install open-cobol
```

Compiling and running the programs
----------------------------------

Create simple COBOL program in the `hello.cbl` file:

```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
    DISPLAY 'Hello world!'.
    STOP RUN.
```

Compile the program with the following command:

```
$ cobc -free -x -o hello hello.cbl
```

Next, we can run the program

```
$ ./hello
```

IDE
---

[OpenCobol IDE](https://github.com/OpenCobolIDE/OpenCobolIDE)

References
----------
- [How to compile and run a COBOL program](http://askubuntu.com/questions/287180/how-to-compile-and-run-a-cobol-program)
- [COBOL on Wikipedia](https://en.wikipedia.org/wiki/COBOL)
- [COBOL tutorials](http://www.tutorialspoint.com/cobol/)
- [node-cobol - running COBOL with node.js](https://github.com/IonicaBizau/node-cobol/)
- [All The Rich Kids Are Into COBOL - But Why?](http://readwrite.com/2014/09/17/cobol-programming-language-hot-or-not)
- [COBOL programming - tutorials, lectures, exercises, examples](http://www.csis.ul.ie/cobol/)
- [3 open source projects for modern COBOL development](https://opensource.com/life/15/10/open-source-cobol-development)
