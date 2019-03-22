# HorizontalGraph

## Requirements
### requiremnt seems helpful to you if you read it carefully

1. Read an arbitrary number of positive integer values from stdin. The values are separated by one or more spaces or newlines (only).
2. The input is guaranteed to be well-formed.
3. On standard output, render a simple graph representation of the input values, in
order, using hash '#' characters as shown in the examples below. The number of
hashes printed should be equal to the input value.
4. Your program should output exactly one line per input value.
5. The value zero should generate an empty line, i.e. just a newline character.
6. Ignore empty lines. Do not output a newline for an empty line.

## Example

1. Input:
5 4 3 2 1 <br>
Output:<br>

     #####
     ####
     ###
     ##
     #

2. Input:
16 0 4 12 <br>
Output: <br>


     ################
     ####
     ############
