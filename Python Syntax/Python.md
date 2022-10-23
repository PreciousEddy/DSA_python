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
  '''boolean = True'''

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
  if <b>cake</b> == "delicious":
      return "Yes please!"
   <b>elif</b> cake == "okay":
       return "I'll have a small piece."
  <b>else:</b>
  	return "No, thank you."
</pre>

## Loops
 <pre>
   <b>for</b> item in <b>list:</b>
  	    print item
   <b>while</b> (total < max_val):
   	     total += values[i]
   	     i += 2
</pre>

## Functions
<pre>
  <b>def divide</b>(dividend, divisor):
  	  quotient = dividend / divisor
    	  remainder = dividend % divisor
  <b>return</b> quotient, remainder
 

   <b>def calculate_stuff</b>(x, y):
         (q, r) = divide(x,y)
   <b>print</b> q, r
</pre>

## Classes
<pre>
   <b>class Person:</b>
  	<b>def__init__</b>(self, name, age):
  	       self.name = name
   	       self.age = age
  
  
  	<b>def birthday</b>():
   	      self.age +=1
</pre>

 
