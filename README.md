README
-------

FIXRobot is software to write testcases and test FIXEngine using FIX Protocol. 

FIXRobot can act as intitiator and acceptor/exchange. 

FIXRobot can send and receive FIX messages and will compare the actual messages with the expected messages.

For documentation please check the docs/index.html.

Usage: import FIXRobot

Author: Written by Anand P. Subramanian.

Copyright: FIXRobot  Copyright (C) 2016  Anand P. Subramanian.

License: GGPLv3+ GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>.

Download: <https://github.com/quickfixrobot/FIXRobot/>

Reporting bugs: <https://github.com/quickfixrobot/FIXRobot/issues>

For enhancements, contributions, collabaration or any questions please contact at <quickfixrobot@gmail.com>

For any issues or enhacements you can also enter the issues in github



Installation Requirements
--------------------------
You have to install the following softwares


PYTHON 2.7
-------
www.python.org


QUICKFIX
--------

This product includes software developed by quickfixengine.org http://www.quickfixengine.org/
Orignially, quickfix is a C++ implementation. So, quickfix module in python is an API to call class and functions of C-module.
http://blog.junmin.info/2015/04/25/a05-quickfix/

Quickfix python API install
For Windows
------------
For windows, no offical guide for compilation yet. Easiest way is using offical built binary package (python 2.7):
x86 & amd64

Installation: 
pip install quickfix-1.14.3-cp27-none-win_amd64.whl
or
pip install quickfix-1.14.3-cp27-none-win32.whl

For Linux
---------
Requirement: gcc, gcc-c++, python-devel (centOS 6)

Installation: pii install quickfix

If the above steps doesnt work for installing quickfix you can try the following steps

pip install quickfix

Python unittest
----------------
Python unittest is part of python standard library and see if its installed by doing "import unittest" in python prompt.
If it is not installed you can try installation: pip install unittest




