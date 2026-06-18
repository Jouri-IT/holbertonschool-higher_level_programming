# holbertonschool-higher_level_programming

python fundamentals coursework from the Holberton School (Tuwaiq) higher-level programming track. each folder is a standalone project covering one concept, with the tasks numbered in the order they were assigned.

---

## overview

this repo is a collection of short python3 scripts and functions, building up from basic syntax to data structures, exceptions, and test-driven development. every script follows the holberton style guide (`#!/usr/bin/python3` shebang, pycodestyle, docstrings) and most are paired with doctests or unit tests.

---

## tech stack

* python 3
* `doctest` / `unittest`
* pycodestyle (pep8) for style checking

---

## repo structure

| folder | concept |
| --- | --- |
| [`python-hello_world`](#python-hello_world) | syntax basics — printing, string formatting, slicing |
| [`python-if_else_loops_functions`](#python-if_else_loops_functions) | conditionals, loops, and functions |
| [`python-import_modules`](#python-import_modules) | importing modules, `sys.argv`, namespaces |
| [`python-data_structures`](#python-data_structures) | lists, tuples, matrices |
| [`python-more_data_structures`](#python-more_data_structures) | sets, dictionaries, comprehensions |
| [`python-exceptions`](#python-exceptions) | try/except/finally, raising exceptions |
| [`python-test_driven_development`](#python-test_driven_development) | tdd with doctests and unittest |

---

## python-hello_world

printing and string basics — escaped quotes, f-strings, slicing, and string concatenation.

<details>
<summary>tasks</summary>

| file | description |
| --- | --- |
| `2-print.py` | prints a string containing an escaped double quote |
| `3-print_number.py` | prints an integer using an f-string |
| `4-print_float.py` | prints a float rounded to 2 decimal places |
| `5-print_string.py` | repeats a string 3 times, then prints its first 9 characters |
| `6-concat.py` | builds a new string by concatenating two variables |
| `60concat.py` | unused/empty file (leftover) |
| `7-edges.py` | slices a string into its first 3 chars, last 2 chars, and middle |
| `8-concat_edges.py` | builds a new string out of slices of a longer string |
| `9-easter_egg.py` | prints the zen of python (`import this`) |

</details>

---

## python-if_else_loops_functions

conditionals, loops, and writing reusable functions.

<details>
<summary>tasks</summary>

| file | description |
| --- | --- |
| `0-positive_or_negative.py` | picks a random number and prints whether it's positive, negative, or zero |
| `1-last_digit.py` | prints a random number's last digit and classifies it (>5, ==0, or <6) |
| `2-print_alphabet.py` | prints the lowercase alphabet, no newline |
| `3-print_alphabt.py` | prints the alphabet skipping 'e' and 'q' |
| `4-print_hexa.py` | prints 0–98 in decimal and hexadecimal |
| `5-print_comb2.py` | prints all numbers from 0 to 100, zero-padded, comma-separated |
| `6-print_comb3.py` | prints all unique 2-digit combinations from 0-9 |
| `7-islower.py` | `islower(c)` — checks if a character is lowercase |
| `8-uppercase.py` | `uppercase(str)` — prints a string in uppercase |
| `9-print_last_digit.py` | `print_last_digit(number)` — prints and returns the last digit |
| `10-add.py` | `add(a, b)` — returns the sum of two numbers |
| `11-pow.py` | `pow(a, b)` — returns a to the power of b |
| `12-fizzbuzz.py` | `fizzbuzz()` — prints 1–100, replacing multiples of 3/5/15 with fizz/buzz/fizzbuzz |
| `100-print_tebahpla.py` | prints the alphabet reversed, alternating case |

</details>

---

## python-import_modules

importing modules, command-line arguments, and namespaces.

<details>
<summary>tasks</summary>

| file | description |
| --- | --- |
| `0-add.py` | imports `add` from `add_0` and prints the result of `1 + 2` |
| `add_0.py` | `add(a, b)` — helper module imported by `0-add.py` |
| `1-calculation.py` | imports add/sub/mul/div from `calculator_1` and prints all four results |
| `calculator_1.py` | `add`, `sub`, `mul`, `div` — basic arithmetic helper module |
| `2-args.py` | prints the number of command-line arguments and lists them |
| `3-infinite_add.py` | sums an arbitrary number of command-line arguments |
| `4-hidden_discovery.py` | lists all public names defined in the `hidden_4` module |
| `5-variable_load.py` | imports and prints a variable (`a`) from `variable_load_5` |
| `variable_load_5.py` | defines the variable imported by `5-variable_load.py` |

</details>

---

## python-data_structures

working with lists, tuples, and matrices.

<details>
<summary>tasks</summary>

| file | description |
| --- | --- |
| `0-print_list_integer.py` | `print_list_integer(my_list)` — prints each integer in a list, one per line |
| `1-element_at.py` | `element_at(my_list, idx)` — gets an element at an index, c-style (no error if out of range) |
| `2-replace_in_list.py` | `replace_in_list(my_list, idx, element)` — replaces an element in place by index |
| `3-print_reversed_list_integer.py` | `print_reversed_list_integer(my_list)` — prints a list of integers in reverse |
| `4-new_in_list.py` | `new_in_list(my_list, idx, element)` — returns a new list with one element replaced, without mutating the original |
| `5-no_c.py` | `no_c(my_string)` — returns a copy of a string with all `c`/`C` removed |
| `6-print_matrix_integer.py` | `print_matrix_integer(matrix)` — prints a 2d list as a formatted matrix |
| `7-add_tuple.py` | `add_tuple(tuple_a, tuple_b)` — adds two tuples element-wise, padding short ones with 0 |
| `8-multiple_returns.py` | `multiple_returns(sentence)` — returns `(length, first_char)` of a string |
| `9-max_integer.py` | `max_integer(my_list)` — returns the largest integer in a list |
| `10-divisible_by_2.py` | `divisible_by_2(my_list)` — returns a list of booleans for which elements are even |
| `11-delete_at.py` | `delete_at(my_list, idx)` — deletes an element at a given index |
| `12-switch.py` | swaps two variables' values in one line and prints both |

</details>

---

## python-more_data_structures

sets, dictionaries, and comprehensions.

<details>
<summary>tasks</summary>

| file | description |
| --- | --- |
| `0-square_matrix_simple.py` | `square_matrix_simple(matrix)` — squares every element of a matrix |
| `1-search_replace.py` | `search_replace(my_list, search, replace)` — replaces all occurrences of a value in a list |
| `2-uniq_add.py` | `uniq_add(my_list)` — sums only the unique elements of a list |
| `3-common_elements.py` | `common_elements(set_1, set_2)` — returns the intersection of two sets |
| `4-only_diff_elements.py` | `only_diff_elements(set_1, set_2)` — returns the symmetric difference of two sets |
| `5-number_keys.py` | `number_keys(a_dictionary)` — returns the number of keys in a dictionary |
| `6-print_sorted_dictionary.py` | `print_sorted_dictionary(a_dictionary)` — prints a dictionary's keys in alphabetical order |
| `7-update_dictionary.py` | `update_dictionary(a_dictionary, key, value)` — sets/updates a key in a dictionary |
| `8-simple_delete.py` | `simple_delete(a_dictionary, key)` — deletes a key from a dictionary if it exists |
| `9-multiply_by_2.py` | `multiply_by_2(a_dictionary)` — returns a new dict with every value doubled |
| `10-best_score.py` | `best_score(a_dictionary)` — returns the key with the highest value |
| `11-multiply_list_map.py` | `multiply_list_map(my_list, number)` — multiplies every list element by a number, using `map` |
| `12-roman_to_int.py` | `roman_to_int(roman_string)` — converts a roman numeral string to an integer |

</details>

---

## python-exceptions

handling errors with try/except/finally and raising custom exceptions.

<details>
<summary>tasks</summary>

| file | description |
| --- | --- |
| `0-safe_print_list.py` | `safe_print_list(my_list, x)` — prints the first x elements of a list, ignoring index errors |
| `1-safe_print_integer.py` | `safe_print_integer(value)` — prints a value as an integer, returns `False` if it isn't one |
| `2-safe_print_list_integers.py` | `safe_print_list_integers(my_list, x)` — prints the first x integers of a list, skipping non-integers |
| `3-safe_print_division.py` | `safe_print_division(a, b)` — divides two numbers, returning `None` on division by zero |
| `4-list_division.py` | `list_division(list_1, list_2, length)` — divides two lists element-wise, handling type/zero/index errors |
| `5-raise_exception.py` | `raise_exception()` — raises a `TypeError` |
| `6-raise_exception_msg.py` | `raise_exception_msg(message)` — raises a `NameError` with a custom message |
| `100-safe_print_integer_err.py` | `safe_print_integer_err(value)` — prints a value as an integer, logging exceptions to stderr |

</details>

---

## python-test_driven_development

writing functions alongside doctests and unit tests (tdd workflow).

<details>
<summary>tasks</summary>

| file | description |
| --- | --- |
| `0-add_integer.py` | `add_integer(a, b)` — adds two numbers, casting floats to int, with doctests |
| `2-matrix_divided.py` | `matrix_divided(matrix, div)` — divides every element of a matrix by a divisor, with input validation |
| `3-say_my_name.py` | `say_my_name(first_name, last_name)` — prints `"My name is <first> <last>"`, validating string inputs |
| `4-print_square.py` | `print_square(size)` — prints a square of `#` characters |
| `5-text_indentation.py` | `text_indentation(text)` — prints text with extra newlines after `.`, `?`, and `:` |
| `6-max_integer_test.py` | unittest suite for a `max_integer` function |

tests live in `tests/`, mirroring each task as a `.txt` doctest file (run with `python3 -m doctest -v tests/<file>.txt`).

</details>

---

## running the scripts

most files are standalone and executable:

```bash
chmod +x ./0-add.py
./0-add.py
```

or run directly with python3:

```bash
python3 ./0-add.py
```

for the test-driven-development project, run doctests with:

```bash
python3 -m doctest -v tests/0-add_integer.txt
```

---

## academic context

coursework completed as part of the **Holberton School × Tuwaiq Academy** software engineering traineeship.
