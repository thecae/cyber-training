# TeLeVision

*You should be able to code this challenge in C.*

## Overview
We are going to write a seeking algorithm that takes in the file `data.bin`, which contains a specialized array that has been serialized.  The algorithm will read the array according to its rules.  The flag can be printed out by printing the first, middle, and 8 characters of the string made using the below constraints.

## Instructions
### Reading the Array
You have been provided `data.bin` which contains the serialized array.  The array is a TLV (Tag-Length-Value) array, where each array contains a Tag, Length, and Value.  Each element takes the following form:
```
| T | L |  Value  |
| 0 | 1 | 2 | ... |
```
The parts of the array entry are:
* *Tag*: An identifier used to classify the type of data that is incoming.
* *Length*: The length of the value.
* *Value*: The value of the data.

You should store all the entries of the array that have prime number tags in a string.  No delimiters should be used in between entries.

### Printing the Flag
The flag is generated by printing the first, middle, and 8 characters of the string created.  *Hint: The string has an even length.*

The flag will be represented in ASCII.  Remember to surround your data in `flag{}` braces.

## Scoring 
When preparing a writeup, you will be evaluated based on the following software engineering pillars:
* Correctness (printing the flag)
* Safe from bugs (handles bad input without crashing)
* Easy to understand (commented and inuitive program structure)
* Ready for change (modular implementation)
* Adherence to the [Google C Style Guide](https://google.github.io/styleguide/cppguide.html).
