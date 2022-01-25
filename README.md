# Notes on Fork

This fork of Mike Naberezny's py65 (https://github.com/mnaberez/py65) consolidates my py65 enhancements, which, while useful to me, are either too specific to my hardware, are works in progress, or aren't of sufficient quality to be contributed to the main branch:

* Support for the W65C816.  See https://github.com/tmr4/py65_65816 for more detail.
* Add debug window. See https://github.com/tmr4/py65_debug_window for more detail.
* Add 65C22 (VIA) and 65C51 (ACIA) support. See https://github.com/tmr4/py65_int for more detail.

# Status

* January 24, 2022
  * I've decided to go in another direction.  Instead of creating my own py65 fork, I'm going to create an add on package that utilizes the py65 modules without modification.  This probably creates some inefficiencies, but has a benefit of not modifying the underlying py65 functionality for those that would rather maintain that package intact.  I've already successfully tested the concept with the 65816 simulation and debug window.  I'll upload the repository shortly, after I've got a local package working.  You can access my work at [py65816](https://github.com/tmr4/py65816).
