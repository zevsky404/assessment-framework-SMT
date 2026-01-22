# Assessment Framework for SMT
An automated assessment framework for SMT tasks given to students in the course of Formal Methods lectures.

## Project Setup
For setting up the project, a `requirements.txt` is provided, which can be used to install all dependencies using `pip`.
To use `pysmt`, an SMT solver has to be installed.

### SMT Solver Installation
1. Install the dependencies.
2. Change the directory to `PYTHONPATH\Lib\site-packages\pysmt\cmd\` (source files of the installed package `pysmt`)
3. Run the command `python install.py --z3` to install the Z3 SMT solver. Other solvers are also available.
