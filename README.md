# Base64
Pictures to base64 encoded strings bulk converter. Speeds up CSS development, preparing **background-image properties** with base64 encoded pictures.
![Example](https://github.com/RobertoPrevato/Base64/blob/master/docs/images/generated-css.png)

**Features**:
- Allows to bulk convert pictures found under a given path, packing base64 encoded strings inside CSS or CSV
- Supports conversion of png, jpg, gif (also animated gif), svg
- Console application with documented interface (includes *--help*)
- Cross platform: being in Python, it can run on Linux, Windows and Mac

**Repository structure**:
- The **source** folder contains the Python source code.
- This code can be executed by both Python 2.x and Python 3.x.
- The **source** folder also contains a setup.py file used with <a href="http://cx-freeze.readthedocs.org/">cx_Freeze</a> to generate the executables.
- The **docs** folder contains information used for this documentation.

Commands
--------------
- -h --help displays the help for the console application
- -p / --path *path* [-m / --mode *mode {css,csv}*] starting from the given folder path, recursively looks for pictures, and generates a single file containing the base64 encoded pictures.
