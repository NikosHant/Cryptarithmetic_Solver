# CryptoSolver
Java code implementing a simple cryptarithmetic solver.

**========================\
Example\
\========================**\
A standard cryptarithmetic riddle would look like this:
  
&emsp;WON  
\+ WON\
\----------  
&emsp; TOO
  
With the goal being mapping each of the given letters to a number in a given base (eg. base 6).\
**========================\
Command Line Arguments\
\========================**

String, String, String, int: The three words that constitute the "equation", followed by the base.

In the above example, the arguments would be: WON WON TOO 6.

**========================\
Source\
\========================**\
This code is based on the example offered [here](https://www.tutorialspoint.com/Solving-Cryptarithmetic-Puzzles),
translated to Java and utilizing data structures and functions offered by Java libraries (ie. HashMap, Math.pow) for quicker/more practical computation.
