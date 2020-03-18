# bfrun
## Overview
BNFC requires a lot of shell commands and dozens of additional files to compile a parser. This script attempts to streamline the process and file cleanup by running everything behind the scenes with one line of code.

## Use
Compile Parser: `bfrun -c <parser_name>.cf`  
Compile and run: `bfrun <parser_name>.cf <input_file>`  
Run: `bfrun -r <input_file>`  
Run (Specific): `bfrun -r <compiled_parser> <input_file>` 
Help: `bfrun -h`  

## License
This is open to anyone who wants to use it in a project, commercial, academic, or otherwise. Just remember to cite your sources.
