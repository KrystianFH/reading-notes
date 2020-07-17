# JavaScript Debugging

### Duckett JavaScript & JQUERY | Chapter 10  | Error Handling & Debugging

In JavaScript, the order in which statements are executed can be complex
  - some tasks cannot be completed until another statement or function has been run.

#### Execution Contexts

Every statement in a script lives in one of three execution contexts:  
- **Global Context**
  - code in the script, but not in a function
  - there is only ONE global context on any page
- **Function Context**
  - code that is being run within a function
  - each function has its own function context
  - **Eval Context**
    - Text is executed like code in an internal function called eval\().

#### Variable Scope

Both Global and Function contexts correspond to the notion of scope:
  - **Global Scope**  
  If a variable is declared outside of a function, it can be used anywhere  
  
    When the *var* keyword is not used when declaring a variable it is placed in global scope.

  - **Function-level Scope**  
  When a variable is declared within a function it can only be used in that function

Understanding execution contexts and stacks is essential when searching for an error in a code.

**Debugging**  
The Process of finding errors.
  - Use the console to help find the location of the error \(by line number)

**JavaScript Errors**  
  There are **seven** types of JavaScript errors:
  - Error
    - generic error which the other errors are based upon
  - SyntaxError
    - syntax has not been followed
  - ReferenceError
    - Tried to reference a variable that is not declared/within scope
  - TypeError
    - An unexpected data type that cannot be coerced
  - RangeError
    - Numbers not in acceptable range
  - URIError
    - encodeURI\(), decodeURI\(), and similar methods used incorrectly
  - EvalError
    - eval\() function used incorrectly

**Try, Catch, Finally**  
If you know you may get an error, handle it gracefully by using try, catch, finally statements.

The try, catch, finally script checks if the JSON can be parsed using a try block before trying to display the information to the user.  
- **Try**
  - If the try statement throws an error, the code in the catch block runs.
- **Catch**  
  - creates a message using the name and message properties of the Error object
- **Finally**  
  - adds a link that allows users to refresh the data they are seeing

[**Return to Home**](README.md)