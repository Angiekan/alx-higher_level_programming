0x0C. Python - Almost a circle
Python
OOP
All your files, classes and methods must be unit tested and be PEP 8 validated.
Write the first class Base:

Create a folder named models with an empty file __init__.py inside - with this file, the folder will become a Python package

Create a file named models/base.py:

Class Base:
private class attribute __nb_objects = 0
class constructor: def __init__(self, id=None)::
if id is not None, assign the public instance attribute id with this argument value - you can assume id is an integer and you don’t need to test the type of it
otherwise, increment __nb_objects and assign the new value to
You will also learn about:

args and kwargs
Serialization/Deserialization
JSON

