# dev-support-py

In this folder, we (will) put supportive codes for Python library development

1. add_files_to_init.py 

by implementing the code above, we can write file names or directory names to __init__.py

Usage: python add_files_to_init.py './dir/'

Example:
 
# Directory structure
./dir/ 

      |__ __init__.py
      
      |__ file1.py
      
      |__ file2.py
      
      |__ folder/


# Output

in __init__.py

#coding: utf-8
from ./dir import file1
from ./dir import file2
from ./dir import folder

