---
title: Python Code Break 2
layout: default
---

## Working with list comprehensions and formatting output

### exercise 1

Rewrite your `remove_from_list function` from yesterday to use a list comprehension to remove the item.

### exercise 2

Write a function `print_freq_results(results)`. This function should take an argument `results` that is a list of tuples like the following:

 ```py
 [
     ('her', 33),
     ('all', 12),
     ('which', 12),
     ('she', 7),
     ('their', 7),
 ]
 ```

 This function should print (not return) output like the following:

 ```sh
   her | 33 *********************************
   all | 12 ************
 which | 12 ************
   she | 7  *******
 their | 7  *******
 ```
