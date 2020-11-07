# Return-vs-Yields
I come across with yield in functions for web scrapping and look into the difference between return and yield in function. The yield is only used when defining a generator function and in the body of the generator function. The yield statement suspends function’s execution and sends a value back to the caller. This allows its code to produce a series of values over time, rather than computing them at once and sending them back like a list.
-with yield you use less memory 
-The yield statement is used to define generators in Python.
-The yield keyword has the unique capability of stopping execution of the function, saving state, and later resuming.
-A return statement ends the execution of the function and sends a value back to the caller.
-A generator is a special function in Python that returns a generator object to the caller rather than a data value. The yield keyword has the unique capability of stopping execution of the function, saving state, and later resuming.

The yield keyword in python works like a return with the only difference is that instead of returning a value, it gives back a generator object to the call.

Python yield returns a generator object. Generators are special functions that have to be iterated to get the values.
Very useful if you have to deal with huge data size as the memory is not used.
Execution time is faster in case of yield for large data size.

Yield returns a generator object to the caller, and the execution of the code starts only when the generator is iterated.	A return in a function is the end of the function execution, and a single value is given back to the caller.

Yield returns a generator object to the caller, and the execution of the code starts only when the generator is iterated.

A return in a function is the end of the function execution, and a single value is given back to the caller.



