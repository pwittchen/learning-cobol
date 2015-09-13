learning-cobol
==============

This repository was created to learn basics of COBOL language and feel some old school vintage breeze

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

References
----------
- [How to compile and run a COBOL program](http://askubuntu.com/questions/287180/how-to-compile-and-run-a-cobol-program)
- [COBOL on Wikipedia](https://en.wikipedia.org/wiki/COBOL)
- [COBOL tutorials](http://www.tutorialspoint.com/cobol/)
- [node-cobol - running COBOL with node.js](https://github.com/IonicaBizau/node-cobol/)
