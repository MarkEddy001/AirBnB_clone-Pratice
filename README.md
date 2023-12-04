# README.md
"""
# AirBnB Clone - The Console

## Description
This project is part of the AirBnB clone project. The goal is to implement a command interpreter for managing AirBnB objects.

## Command Interpreter
### How to Start It


### How to Use It
Command syntax here...

### Examples
Example usage here...
"""

# AUTHORS
"""
Wanyoike Edwards <wanyoike@example.com>
Whitney Oduor <whitney@example.com>
"""

# main.py (this is a skeleton for the console)
#!/usr/bin/python3
import cmd

class HBNBCommand(cmd.Cmd):
    """Command processor for AirBnB clone."""
    
    prompt = '(hbnb) '

    def do_EOF(self, line):
        """Exit the program"""
        return True

    def do_quit(self, line):
        """Quit command to exit the program"""
        return True

    # More command methods go here

if __name__ == '__main__':
    HBNBCommand().cmdloop()

# __init__.py inside tests directory to make it a package
# tests/__init__.py
"""

# __init__.py inside test_models to make it a package
# tests/test_models/__init__.py
"""

# test_base_model.py with a skeleton for future tests
# tests/test_models/test_base_model.py
#!/usr/bin/python3
import unittest

class TestBaseModel(unittest.TestCase):
    """Unit tests for BaseModel"""
    
    def setUp(self):
        pass

    def test_something(self):
        pass

    # More tests will go here

if __name__ == '__main__':
    unittest.main()

