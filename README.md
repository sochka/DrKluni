# Dr. Kluni [![Build Status](https://travis-ci.org/sochka/DrKluni.png)](https://travis-ci.org/sochka/DrKluni)

This is a program which solves a problem of virtual doctor called "Dr. Kluni" for testing author's skill.


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

        $ ./drkluni
        K1 M K2 P2 L2

* arguments throught command line options

        $ ./drkluni K1 M K2 P2 L2

* test using prewritten test-cases

        $ ./drkluni --test

## Notes
* The actual prolem-solving code is located in src/DrKluniHelper.cpp in contructor
* Algorithm running time is &Theta;(1) for special cases and &Omicron;(min(K1,K2)) for the worst case
