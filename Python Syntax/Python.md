# Refreshing Python

## Comments

 This is a one-line comment - code blocks are so useful!

 > ''' This type of comment is used to document the purpose of functions and classes.'''

## Declaration/Initializations

  Remember values, not variables, have data types.

  A variable can be reassigned to contain a different data type.

 > answer = 42<br>
 > answer = "The answer is 42."


## Data Types
<pre>
  **boolean = True**

  number = 1.1

  string = " Strings can be declared with single or double quotes."

  list = ["Lists can have", 1, 2, 3, 4, "or more types together!"]

  tuple = ("Tuples", "can have", "more than", 2, "elements!") 

  dictionary = {'one': 1, 'two': 2, 'three': 3}

  variable_with_zero_data = None

</pre>

## Simple Logging

 > print "Printed" 

## Conditionals

  Pay attention to the indentation always.  
<pre>
   **if** cake == "delicious":
      return "Yes please!"
   **elif** cake == "okay":
       return "I'll have a small piece."
   **else:**
  	return "No, thank you."
</pre>

## Loops
 <pre>
   **for** item in **list:**
  	    print item
   **while** (total < max_val):
   	     total += values[i]
   	     i += 2
</pre>

## Functions
<pre>
  **def divide**(dividend, divisor):
  	  quotient = dividend / divisor
    	  remainder = dividend % divisor
     	  **return** quotient, remainder
 

   **def calculate_stuff**(x, y):
         (q, r) = divide(x,y)
  	  **print** q, r
</pre>

## Classes
<pre>
   **class Person:**
  	**def**__init__(self, name, age):
  	       self.name = name
   	       self.age = age
  
  
  	**def birthday**():
   	      self.age +=1
</pre>

 
