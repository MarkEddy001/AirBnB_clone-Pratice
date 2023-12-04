# AirBnB Clone - The Console

## Project Description

Welcome to the AirBnB clone project! This project is a group effort by Wanyoike Edwards and Whitney Oduor, mentored by Guillaume. The goal is to build a command-line interpreter to manage AirBnB objects, laying the foundation for a complete web application.

## Table of Contents

- [Background Context](#background-context)
- [Concepts](#concepts)
- [Requirements](#requirements)
- [How to Use](#how-to-use)
- [Examples](#examples)
- [Authors](#authors)

## Background Context

Before diving into the project, make sure to read the AirBnB concept page. 
The project involves creating a parent class (BaseModel) for object initialization, serialization, and deserialization. 
It includes the implementation of a simple flow for serialization/deserialization, creation of AirBnB-related classes, and development of a file storage engine. 
The project also emphasizes the importance of unit testing, Python packages, and handling various concepts such as datetime, UUID, and command-line arguments.

## Concepts

- Python packages
- AirBnB clone
- Command-line interpreter
- Serialization and deserialization
- Unit testing
- File storage engine
- Datetime, UUID, and command-line arguments

## Requirements

Make sure to check the [Requirements](#requirements) section for details on script execution, allowed editors, file organization, and unit tests.

## How to Use

## Interactive Mode

```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
```

## Non-Interactive Mode

```bash
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)

```
## Examples

Create a new User:
```bash
(hbnb) create User
```
Retrieve an object from a file:
```bash
(hbnb) show User 1234-5678
```
Update attributes of an object:
```bash
(hbnb) update User 1234-5678 name "John Doe"
```
Destroy an object:
```bash
(hbnb) destroy User 1234-5678
```
## Authors

`Wanyoike Edwards`
`Whitney Oduor`

For a full list of contributors, check the [AUTHORS](#AUTHORS) file.
