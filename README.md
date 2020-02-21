# PhysiCell_1.6.1_sbml


## Overview: 
Demonstrate using PhysiCell togetheer with an intracellular (metabolic) model (represented as a SBML file) which is solved using libRoadRunner.

## Dependencies
* modern g++ compiler (rf. Quickstart)
* Python 3 (Anaconda distribution recommended)

## Instructions
```
$ cd beta
$ python setup_libroadrunner.py
```
Follow instructions from that Python script, including editing the PhysiCell Makefile. Then:
```
$ make
$ ftest
```
However, on Windows, it seems you must first edit your PATH environment variable to include the path to the .dll, i.e., the LIBRR_LIBS path (and then open a new Command Prompt window for it to take effect).
