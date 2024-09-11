# Python Interview Questions and Answers

This repository contains **100 Python Interview Questions** divided into Easy, Intermediate, and Hard sections. These questions cover the core concepts and help you prepare for Python-related interviews.

## Table of Contents

1. [Easy Questions](#easy-questions)
2. [Intermediate Questions](#intermediate-questions)
3. [Hard Questions](#hard-questions)

---

## Easy Questions

| #   | Question                                               | Answer                                                                 |
|-----|---------------------------------------------------------|------------------------------------------------------------------------|
| 1   | What is Python?                                         | Python is a high-level, interpreted, general-purpose programming language. |
| 2   | What are Python's key features?                         | Interpreted, dynamically-typed, object-oriented, and has a vast standard library. |
| 3   | How do you create a variable in Python?                 | By assigning a value to it (e.g., `x = 10`).                            |
| 4   | How do you write comments in Python?                    | Using the `#` symbol for single-line comments, or triple quotes `'''` for multi-line comments. |
| 5   | What is a function in Python?                           | A reusable block of code that performs a specific task, defined using the `def` keyword. |
| 6   | What is the difference between a list and a tuple in Python? | A list is mutable, whereas a tuple is immutable.                        |
| 7   | How do you create a list in Python?                     | By placing elements within square brackets: `my_list = [1, 2, 3]`.      |
| 8   | How do you create a tuple in Python?                    | By placing elements within parentheses: `my_tuple = (1, 2, 3)`.         |
| 9   | How do you create a dictionary in Python?               | Using curly braces with key-value pairs: `my_dict = {'a': 1, 'b': 2}`.  |
| 10  | How do you create a set in Python?                      | By placing elements within curly braces: `my_set = {1, 2, 3}`.          |
| 11  | How do you check the type of an object in Python?       | Using the `type()` function.                                            |
| 12  | What is the difference between `==` and `is` operators? | `==` checks value equality, whereas `is` checks identity (whether two objects are the same in memory). |
| 13  | How do you handle exceptions in Python?                 | Using `try`, `except`, `finally` blocks.                                |
| 14  | What is the purpose of the `range()` function?          | To generate a sequence of numbers.                                      |
| 15  | How do you concatenate strings in Python?               | Using the `+` operator or `join()` method.                              |
| 16  | What are Python's built-in data types?                  | `int`, `float`, `str`, `list`, `tuple`, `set`, `dict`, `bool`.          |
| 17  | How do you define a class in Python?                    | Using the `class` keyword followed by the class name and a colon.       |
| 18  | What is an instance in Python?                          | An object created from a class.                                         |
| 19  | What is the difference between local and global variables in Python? | Local variables are defined within a function, whereas global variables are defined outside any function. |
| 20  | How do you import a module in Python?                   | Using the `import` statement (e.g., `import math`).                     |

---

## Intermediate Questions

| #   | Question                                               | Answer                                                                 |
|-----|---------------------------------------------------------|------------------------------------------------------------------------|
| 21  | What is list comprehension in Python?                   | A concise way to create lists using a single line of code.              |
| 22  | How do you perform list comprehension?                  | `[expression for item in iterable]`.                                    |
| 23  | What is the `map()` function in Python?                 | Applies a function to every item of an iterable and returns an iterator.|
| 24  | What is the `filter()` function in Python?              | Filters items from an iterable based on a function and returns an iterator.|
| 25  | What is the difference between `map()` and `filter()`?  | `map()` applies a function to each element, while `filter()` removes elements that don’t meet a condition. |
| 26  | How do you use the `reduce()` function?                 | By applying a function cumulatively to items in an iterable to reduce it to a single value (requires `functools`). |
| 27  | What is a lambda function?                              | An anonymous, inline function defined using the `lambda` keyword.       |
| 28  | What is the difference between `None` and `False` in Python? | `None` represents the absence of a value, while `False` is a boolean value. |
| 29  | How do you reverse a list in Python?                    | Using `list.reverse()` or `reversed(list)`.                             |
| 30  | How do you create a generator in Python?                | Using a function with `yield` instead of `return`.                      |
| 31  | What is the `with` statement used for?                  | It simplifies exception handling by encapsulating common preparation and cleanup tasks. |
| 32  | How do you handle files in Python?                      | Using `open()`, `read()`, `write()`, and `close()` methods.             |
| 33  | How do you sort a list of dictionaries by a key?        | By using the `sorted()` function with a key argument.                   |
| 34  | How do you merge two dictionaries in Python?            | Using the `update()` method or `{**dict1, **dict2}`.                    |
| 35  | What is the purpose of the `zip()` function?            | To combine two or more iterables into tuples.                           |
| 36  | How do you check if a key exists in a dictionary?       | Using the `in` operator (e.g., `if key in my_dict`).                    |
| 37  | What is the `del` statement used for?                   | To delete objects, variables, list elements, or dictionary keys.        |
| 38  | What is the difference between deep copy and shallow copy? | A deep copy copies all objects recursively, while a shallow copy copies only the top-level object. |
| 39  | What is the purpose of the `enumerate()` function?      | It adds a counter to an iterable and returns it as an enumerate object.  |
| 40  | How do you create an infinite loop in Python?           | By using `while True:` without a breaking condition.                    |
| 41  | What is the purpose of the `global` keyword?            | To declare that a variable inside a function refers to a globally defined variable. |
| 42  | How do you remove duplicates from a list?               | By converting the list into a set and back into a list: `list(set(my_list))`. |
| 43  | How do you convert a list of strings to integers?       | Using list comprehension with `int()` function: `[int(x) for x in my_list]`. |
| 44  | What is the difference between `sort()` and `sorted()`? | `sort()` sorts a list in-place, while `sorted()` returns a new sorted list. |
| 45  | How do you handle JSON data in Python?                  | Using the `json` module to `load()`, `dump()`, `loads()`, and `dumps()`. |
| 46  | How do you create a virtual environment in Python?      | Using the `venv` module: `python -m venv env_name`.                     |
| 47  | How do you check for memory leaks in Python?            | By using tools like `gc` module or `memory_profiler`.                   |
| 48  | What is the `__name__` variable in Python?              | It holds the name of the current module. If the module is being run directly, it will be `'__main__'`. |
| 49  | What is a decorator in Python?                          | A function that modifies the behavior of another function or method.    |
| 50  | How do you create a decorator?                          | By defining a function that returns another function, using the `@` symbol before the function name. |

---

## Hard Questions

| #   | Question                                               | Answer                                                                 |
|-----|---------------------------------------------------------|------------------------------------------------------------------------|
| 51  | What is the Global Interpreter Lock (GIL)?              | A mutex that protects access to Python objects, preventing multiple threads from executing Python bytecodes simultaneously. |
| 52  | How do you implement multithreading in Python?          | Using the `threading` module to create and manage threads.             |
| 53  | How do you handle multiprocessing in Python?            | Using the `multiprocessing` module to create and manage processes.     |
| 54  | What are metaclasses in Python?                         | Metaclasses are classes of classes that define how classes are created and behave. |
| 55  | How do you create a metaclass?                          | By defining a class that inherits from `type`.                         |
| 56  | What is monkey patching?                                | The dynamic modification of a class or module at runtime.              |
| 57  | How do you implement method overloading in Python?      | Python does not natively support method overloading. You can implement it using default arguments or variable-length arguments. |
| 58  | What is method overriding?                              | Redefining a method in a subclass that was originally defined in the parent class. |
| 59  | How does Python's garbage collection work?              | Python uses reference counting along with a cyclic garbage collector to free memory. |
| 60  | How do you use `asyncio` in Python?                     | By using `async def` to define coroutines and `await` to yield control during blocking operations. |
| 61  | What is a coroutine?                                    | A coroutine is a function that can pause its execution and return control to the event loop, resuming later. |
| 62  | How do you handle exceptions in asynchronous code?      | Using `try` and `except` blocks inside `async` functions or handling exceptions in the event loop. |
| 63  | How do you profile Python code performance?             | By using modules like `cProfile` and `timeit` to measure execution time and performance bottlenecks. |
| 64  | What is a closure in Python?                            | A closure is a function that remembers the values from its lexical scope even when the program flow is no longer in that scope. |
| 65  | What is the `nonlocal` keyword?                         | It allows a function to modify variables from the nearest enclosing scope that is not global. |
| 66  | What is `functools.lru_cache`?                          | A decorator that caches the results of function calls to improve performance. |
| 67  | What is duck typing in Python?                          | Duck typing refers to Python's dynamic typing, where an object's suitability is determined by its methods and properties rather than its type. |
| 68  | How do you manage memory in Python?                     | By avoiding circular references, using weak references, and monitoring object lifetimes. |
| 69  | What is a weak reference in Python?                     | A weak reference allows one to reference an object without preventing its garbage collection. |
| 70  | How do you serialize and deserialize objects in Python? | By using the `pickle` module to convert objects to byte streams and back. |
| 71  | What is a context manager in Python?                    | A context manager allows setup and cleanup operations around a block of code using `with` statements. |
| 72  | How do you create a custom context manager?             | By defining a class with `__enter__` and `__exit__` methods or using the `contextlib` module. |
| 73  | What is the `dataclasses` module in Python?             | It provides a decorator and functions for automatically adding special methods to user-defined classes. |
| 74  | How do you enforce immutability in Python?              | By using `namedtuple`, `frozenset`, or custom classes with overridden setters. |
| 75  | What are slots in Python?                               | Slots are a mechanism to restrict dynamic attribute creation in objects by using the `__slots__` attribute in a class. |
| 76  | What is the difference between `@staticmethod` and `@classmethod`? | `@staticmethod` defines a method that doesn't access the instance or class, while `@classmethod` takes a `cls` argument that refers to the class. |
| 77  | How do you perform type hinting in Python?              | By specifying the expected types of function arguments and return values using annotations. |
| 78  | How do you implement singleton design pattern in Python?| By using a metaclass or overriding the `__new__` method.               |
| 79  | What are Python descriptors?                           | Descriptors are objects that manage the attributes of other objects through methods like `__get__`, `__set__`, and `__delete__`. |
| 80  | How do you use `property()` in Python?                  | To create getter, setter, and deleter methods for class attributes.    |
| 81  | What is the Observer design pattern in Python?          | A pattern where an object (subject) notifies observers (listeners) about changes. |
| 82  | How do you create threads in Python?                    | Using the `threading` module by creating `Thread` objects.             |
| 83  | What is a deadlock in Python?                           | A situation where two or more threads are blocked forever, waiting for each other to release resources. |
| 84  | How do you prevent deadlocks in Python?                 | By using locks, semaphores, or avoiding circular waits.                |
| 85  | What is the difference between a thread and a process?  | A thread is a lightweight process that shares memory space, while a process has its own memory space. |
| 86  | How do you use `heapq` in Python?                       | By using the `heapq` module to implement a priority queue with a heap. |
| 87  | What is memoization in Python?                          | A technique to store function call results to avoid recalculating for the same inputs. |
| 88  | How do you dynamically load a module in Python?         | By using `importlib.import_module()`.                                  |
| 89  | What is reflection in Python?                           | The ability of a program to inspect and modify its structure and behavior at runtime. |
| 90  | How do you get the name of the currently executing function in Python? | Using `inspect.currentframe().f_code.co_name`.                        |
| 91  | How do you create an abstract base class in Python?     | By importing `ABC` from the `abc` module and using `@abstractmethod` decorator. |
| 92  | What is the Chain of Responsibility design pattern?     | A pattern where requests are passed along a chain of handlers until one handles it. |
| 93  | What is method resolution order (MRO)?                  | The order in which Python looks up methods in a class hierarchy, used in multiple inheritance. |
| 94  | How do you achieve multiple inheritance in Python?      | By specifying multiple base classes in a class definition.             |
| 95  | What is a metaclass conflict in Python?                 | It occurs when a class inherits from two classes with incompatible metaclasses. |
| 96  | How do you detect circular dependencies in Python?      | Using tools like `pydeps` or by manually inspecting the module import graph. |
| 97  | How do you implement the State design pattern in Python?| By creating a state base class and specific state subclasses, switching states dynamically. |
| 98  | What is the purpose of `super()` in Python?             | To call methods from a parent class in a subclass, typically during method overriding. |
| 99  | How do you make Python code faster?                     | By using tools like `Cython`, optimizing loops, using `numpy`, and reducing function calls. |
| 100 | How do you deal with memory fragmentation in Python?    | By avoiding large object allocations and using `pymalloc` or memory profilers to manage memory efficiently. |

---

## Contribute

Feel free to contribute to this repository by adding more questions or improving existing ones!

