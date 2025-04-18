﻿# JSParserWithAntlr4
Before running, go install the antlr tools and antlr runtime environment first.
Note: the project is run on Windows
```batch
pip install antlr4-tools
pip install antlr4-python3-runtime==4.13.2
```
If the `antlr4-tools` is not installed within the conda environment, you might want to manually add it (usually under the `..\LocalCache\local-packages\Python310\Scripts`) to the enviromental paths (For details, see the official webpage of [Antlr4](https://www.antlr.org/)). 
All the required preprocessing steps have been done for JS in python3 environments in this project. 

To traverse the JS AST of the test code `config-ucharts.js`, run the following code:
```batch
python driver.py config-ucharts.js
```
To run your own JS code, add your file `xx.js` under the project directory, and the run:
```batch
python driver.py {your_filename.js}
```
