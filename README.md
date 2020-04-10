# coreValueFinder
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)

This script helps selecting your core values from a list heuristically.
It shows 3 randomly choosen core values and asks to select the one that resonates most.
The session management enables continuation at a later point.

## HOW TO

`$ python3 main.py` or `$./main.py`

## COMMANDS

* `[1-3]` : select the most important core value of the ones shown
* `[0]` : non of the shown core values are important
* `[STRG]+D` OR `[STRG]+C` : save the session, show results and exit

## ARGUMENTS
* `--no-descr` : deactivate core value description (if available in the value set)
