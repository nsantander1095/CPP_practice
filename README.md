# C++ Practice and Notes
Just a place to start learning C++ basics.

## Beginner Notes

* ```std::cout``` is the character output stream. it is pronounced C-out
* ```<<``` is an operator that comes right after it
* ```"Hello World!\n"``` is what is being poutput in the simple hello function. __Need double quotes around text__. The ```\n``` is a newline character
* ```;``` is a punctuation that tell sht ecomputer that youa re at the end of a statemenet. It is similar to a period in a sentence.
* ```//``` Single line comment header, ```/* Comments */``` for multiple line comments.
* ```#include <iostream>``` this is known as a pre-processor directive, It instructs the compiler to locate the file that contains code for a library known as ```iostream```. This library contains code that allows for input and output, such as displaying data in the terminal window or reading input from your keyboard
* ```
  int main() {
  // Statements
  }
  ```
  Every C++ program must have a function called ```main()```. A function is basically a sequence of instructions for the computer to execute. This ```main()``` function houses all of our instructions for our program. This is where we will be writing our code. 
* ```return 0;``` The return statement is used to end a function. If the program reaches this sytatement, returning a value of ```0``` is an indication to the operating system that the code executed successfully. Thisw line of code is optional. 
* __It is highly reccomended you make use of white space to indent and seperate lines of code to aid in the readability of your source code files.__

## Compiling and executing

* __Compile__: To compile a file, you need to type ```g++``` followed by a space and then the file name in the terminal and then press enter. Compiler translates to a machine code file called ```a.out```.

* __Execute__: To execute the machine code file, all you need to do is type ```./``` and the machine code file name in the terminal and press enter. In this case, being ```a.out```.

* Naming executables: First type ```g++``` followed by a space and the filename and then a space followed by ```-o``` and a space and then the file name you want for the executable file. Execute the same way.

## Variables

| Type | Usage | Examples |
| ---- | ----- | -------- |
| int | integer numbers | 0, 420|
| double | floating-point numbers | 3.14, -200.0 |
| char | characters | 'a','@' |
| string | sequence of characters | "Hello world!", "Codecademy" |
| bool | truth values | true false |

### Initialization Examples
* ```int age = 28;```
* ```double price = 8.99;```
* ```char grade = 'A';```
* ```std::string message = "Game Over";```
* ```bool late_to_work = true;```

### User Input

* ```cin``` refers to the standard input stream (pronounced c-in) for character input.
* ```>>``` operator that specifies where that input goes

### Datatype Modifiers

* Datatype modifiers are used with built-in data types to modify the length of data that a particular data type can hold. Data type modifiers in C++ are:
  * ```signed```
  * ```unsigned```
  * ```short```
  * ```long```

* ```const``` -constant variables cannot be changed by your program during execution
* ___Type Conmversion___ - A type cast is basically a conversion from one type to another. The notation ```(type) value``` means "convert ```value``` to ```type```".
  * Example:
  ```
  double weight1;
  int weight2;
  weight1 = 154.49;
  weight2 = (int) weight1;
  // weight2 is now 154
  ```
  * ___Conversion from ```double``` to ```int``` does not round.___
