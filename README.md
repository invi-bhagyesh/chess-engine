Chess Engine
============

This is a small chess engine written cause it feels cool. It is can hold a chess via command line or through any UCI compatible chess board.

Installation
-----------

    cd src && make

It will work on OS X, but almost all of the engine is compatible with UNIX like systems more generally and will compile via gcc with just a few changes.

Those interested are unlikely to be able to compile on Windows at the moment due to reliance on POSIX threads. Documentation can also be generated via Doxygen in the root directory.

Running
-------

Once installed, the engine can be run simply by executing it as an executable at the command line. Typing help at the resultant prompt will give a list of commands and a description of their usage.

Alternatively, running with --uci as a first parameter and the location of a file to log to as the second will start the engine in UCI mode, useful for configuration with a chess board GUI.

