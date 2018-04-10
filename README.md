# ToC

## Build

To build the project, cd into working directory and enter `make`.
A `go` file will be generated.

## Run

To run the `go` executable, enter `./go` on the cli.
To direct file input into the executable, enter `./go < filename`

## Input

An input file should adhere to the following specification:
(variable names and sample data are examples only)

* `vari x`: Integer variable declaration   
* `vars y`: String variable declaration    
* `y = 5`: Integer assignment statement   
* `g = "hello world"`: String assignment statement
* `set x to 3 * y`: Assignment statement
* `printsh g`: Instruction to print a string horizontally
* `printsv g`: Instruction to print a string vertically

## Output

Output will be in the form of a C file.

## Errors

Errors will be thrown in the following cases:

* Assignment to incorrect type
* Declaring previously declared variables

## Clean

From the working directory, enter `clean`
