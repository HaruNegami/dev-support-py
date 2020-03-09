# dev-support-py

In this folder, we (will) put supportive codes for Python library development

1. add_files_to_init.py 

by implement the code above, we can write file names or directory names to __init__.py

Usage: python add_files_to_init.py './dir/'

Example:

./dir/ -- __init__.py
       -- file1.py
       -- file2.py
       -- folder/


#__init__.py

# coding: utf-8

from ./dir import file1
from ./dir import file2
from ./dir import folder

