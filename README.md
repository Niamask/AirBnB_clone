# AirBnB Clone - The Console

![hbnb](https://github.com/Niamask/AirBnB_clone/assets/94907249/18d109d9-023b-48e8-a64f-328242882f07)

## Table of contents:
* [Description](#Description)
* [Installation](#Installation)
* [Execution](#Execution)
* [Available Command](#Available-Command)
* [Authors](#Authors)


## Description:
The console (command line interepteur) is the first segment of the AirBnB project that will collectively cover the fundamental concepts of higher level programming.
The goal is to build a full web application: the AirBnB clone.

## Installation:
- Clone This Repo git clone https://github.com/Niamask/AirBnB_clone.git
- Access AirBnb directory: cd AirBnB_clone
- Run hbnb(interactively): ./console and enter command
- Run hbnb(non-interactively): echo "<command>" | ./console.py

## Execution

In interactive mode

```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

in Non-interactive mode

```bash
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```

## Available Command:
- quit and EOF to exit the program
- help for every Command
- create
- show
- destroy
- all
- update
- count

## Authors 
- Niama SKAY
- Hind Ouchani
