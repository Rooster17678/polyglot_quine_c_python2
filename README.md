Polyglot-Quine
==============

By Jake Pennington
------------------

This program is a quine that is simultaneously valid in C and Python2.

### Running

The program compiles with gcc version 8.1.0 and also runs with Python 2.7.9.

The claims can be verified using diff.
Example:

> gcc pgq.c -o pgq
>
> diff <(./pgq) <(python2 pgq.c)
>
> diff pgq.c <(./pgq)

### Note:

The C and C++ files are two slightly different examples.  Both work with Python2.

### Github

https://github.com/Rooster17678/polyglot_quine_c_python2.git
