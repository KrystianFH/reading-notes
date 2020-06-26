# Operators and Loops | JavaScript and JQUERY | Jon Duckett

### Comparison Operators

__= =__
>is equal to  
- compares two values to see if they are the same
- 'Hello' = = 'Goodbye returns as _false_
- 'Hello' = = 'Hello' returns as _true_

__= = =___
>strict equal to  
- compares two values to check that both the data type and value are the same
- '3' = = = 3 returns as _false_
- '3' = = = '3' returns as _true_

__! =__
>is not equal to
- compares two values to see if they are __not__ the same
- 'Hello' ! = 'Goodbye' returns _true_
- 'Hello' ! = 'Hello' returns as _false_

__! = =__
>strict not equal to
- compares two values to check that both the data type and value are __not__ the same
- '3' ! = = 3 returns as _true_
- '3' ! = = '3' returns as _false_

__>__
>greater than
- checks if the number on the left is _greater than_ the number on the right
- 4 > 3 returns as _true_
- 3 > 4 returns as _false_

__> =__
>greater than or equal to
- checks if the number on the left is _greater than or equal to_ the number on the right
- 4 > = 3 returns as _false_
- 3 > = 4 returns as _false_
- 3 > = 3 returns as _true_

__<__
>less than
- checks if the number on the left is _less than_ the number on the right
- 4 < 3 returns as _false_
- 3 < 4 returns as _true_

__< =__
>less than or equal to
- checks if the number on the left is _less than or equal to_ the number on the right
- 4 < = 3 returns as _false_
- 3 < = 4 returns as _true_
- 3 < = 3 returns as _true_

### Logical Operators

Logical operators allow the user to compare the results of more than one element

__& &__
>logical and
- tests more than one condition
- ((2 < 5) & & (3 > = 2)) returns as _true_
- if either expressions evaluate to _true_ than the expression returns true.
- true & & true returns _true_
- true & & false returns _false_
- false & & true returns _false_
- false & & false returns _false_

__| |__
>logical or
- tests at least one condition
- ((2 < 5) | | (2 < 1)) returns as _true_
- if either expression evaluates to _true_ then the expression returns _true_
- true & & true returns _true_
- true & & false returns _true_
- false & & true returns _true_
- false & & false returns _false_

__!__
>logical not
- takes a single Boolean value and inverts it
- ! (2 < 1) returns as _true_
- This reverses the state of the expression
- ! _true_ returns as _false_
- ! _false_ returns as _true_

### Loops

Loops check a condition, and if that condition is true than a block of code will run. The condition is checked again and again if it still returns true, until it returns false. 

__Types of Loops__
1. For 
    - Used to run a code a specific number of times (__*most common*__)
1. While
    - Used when you are unsure of how many loops that should be run. 
    - The code will continue to run as long as the condition is _true_
1. Do While
    - Similar to the while loop but will always run the curly bracket statements at least once even if the condition evaluates to _false_

### Loop Counters

A __for__ loop uses a counter as a condition. 

Conditions are made up of three statements:  
1. _Initialization_
    - Create a variable and set it to 0. 
    - This variable is called 'i' and acts as the counter
    - __var i = 0;__
        - created only the first time the loop is run.
    - sometimes declared before the condition
    - i might also be called _index_

2. _Condition_
    - Allows the loop to run until the counter reaches a specified number
    - __i < 10;__
        - the value of i was initially set to 0, so the loop will run 10 times before stopping
    - the condition may also use a variable that holds a number
        - if the variable called _rounds_ held the number of rounds in a test and the loop ran once for each round, the condition would appear as:
            - _var rounds = 3;_  
              _i < (rounds);_

3. _Update_
    - every time the loop has run the statements in the curly brackets it adds one to the counter
        - __i++__
            - one is added to the counter using the + + operator
            - read as "take the variable __i__ and add one using the + + operator"
    - loops can count down by using the decrement operator:
        - __- -__ 
              
[**Return to Home**](README.md)