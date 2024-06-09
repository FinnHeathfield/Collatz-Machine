# Collatz Machine
 An audio generator based on the Collatz Conjecture

The Collatz Conjecture posits:

Take a number:

If the number is odd, multiply it by 3 and add 1 (3x+1

If the nubmer is even, divide it by 2.

By repeating this sequence of steps, numbers will always fall into a 4-2-1 loop. 

The patch takes a random starting value for 3 voices which each then go through this process with each iteration of the numbers being converted to a frequency of an oscilator. When the 4-2-1 loop is reached, a new random value is generated and the process is repeated. 
