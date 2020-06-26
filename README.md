# Python-Calculator
A scientific calculator GUI using the TkInter library

My calculator contains a basic arithmetic function which performs math operations on two numbers and a calculator
function which takes in a mathematical equation as a string argument and outputs the numbers.

This calculator can calculate any amount of numerical terms.

This calculator takes into account precedence of operators (exponentials first, then multiply and divide, and finally
addition and subtraction). This calculator can also interpret precedence through brackets (eg. (x+y)/z will evaluate
(x+y) first.)

The **ConsoleCalculator.py** file contains the functions required to perform calculations based on a formula string.
At the bottom of this file is a commented-out script. Remove the triple quotations (''') to run the calculator program
using the Python console.


The **CalculatorApp.py** file implements the functions from **ConsoleCalculator.py** through a TkInter GUI. Please
ensure that the commented script at the end of **ConsoleCalculator.py** remains commented out to suppress the console
outputs.
