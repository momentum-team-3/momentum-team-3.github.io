---
layout: post
title: 'Curated Python Cheats Sheet'
tags: phase-2 python helper
---

In response to some questions this afternoon, I put together a list of Python builtin functions 
and keywords. Because there are a LOT of keywords and builtin functions, I've tried to pare these
down to those we're going to be using or otherwise most likely to encounter (I've included links
to the full lists at the bottom of this document.


### Python Builtin Functions (does not include methods)

In the table below, 'constructors' will return an object of the indicated type, 'sequences' will
return a sequence we can use in a for loop, 'tests' will return True or False, input/output will
interact with external resources, and 'general' fall into none of the above categories.

| constructors | sequences   | general | tests        | input/output |
|--------------|-------------|---------|--------------|--------------|
| `list`       | `range`     | `len`   | `callable`   | `print`      |
| `str`        | `zip`       | `max`   | `isinstance` | `input`      |
| `dict`       | `enumerate` | `min`   | `hasattr`    | `open`       |
| `tuple`      |             | `sum`   |              | `exit`       |
| `int`        |             | `type`  |              |              |
| `float`      |             |         |              |              |
|              |             |         |              |              |


### Python Keywords

In the table below, 'looping' keywords introduce a block that will be repeated some number of
times, 'conditional' keyword separate blocks that should only be executed conditionally, 
'expression' keywords produce a value (so far these are all booleans), and 'other' is a
catchall for keywords that introduce other kinds of blocks.

| looping  | conditional | expression | other     |
|----------|-------------|------------|-----------|
| `for/in` | `if`        | `in`       | `def`     |
| `while`  | `elif`      | `not`      | `class`   |
|          | `else`      | `and`      | `with/as` |
|          |             | `or`       | `try`     |
|          |             |            | `except`  |
|          |             |            | `import`  |
|          |             |            | `raise`   |
|          |             |            |           |

### Common Python Modules

All of these modules are in the Python Standard Library. The column heading indicates the subject
of the module.

| operating system | math utilities | data processing and storage | utilities   |
|------------------|----------------|-----------------------------|-------------|
| os               | math           | pickle                      | string      |
| sys              | statistics     | json                        | datetime    |
| pathlib          | random         | csv                         | collections |
|                  |                |                             | pdb         |
|                  |                |                             |             |


### Links to Comprehensive Resources

-[Full List of Python Builtin Functions, with Documentation](https://docs.python.org/3/library/functions.html)
-[Full List of Python Keywords](https://www.w3schools.com/python/python_ref_keywords.asp)
-[Python Keyword/Language Documentation](https://docs.python.org/3/reference/index.html)
-[List of Python Standard Library Modules, with Documentation](https://docs.python.org/3/library/index.html)
