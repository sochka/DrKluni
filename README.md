Dr. Kluni
======================
This is a program which solves a problem of virtual doctor called "Dr. Cluni" for testing author's skill.


## Build 
This program should be cross-platform but tested only with g++

    $ git clone git@github.com:sochka/DrKluni.git
    $ cd DrKluni
    $ mkdir build
    $ cd build
    $ cmake ../src
    $ make

## Run
* arguments through stdin

   $ ./drcluni  
   K1 M K2 P2 L2

* arguments throught command line options

    $ ./drcluni K1 M K2 P2 L2

* test using prewritten test-cases

    $ ./drcluni --test