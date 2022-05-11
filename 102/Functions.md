# **Programming with JavaScript**

### **Control Flow**

Code runs in order from the first to last line unless something in the code modifies the control flow. This means it is important to consider where you want to start and how the program should run when you are creating the code.

### **JavaScript Functions**

A function is a block of code designed to perform a specific task. In JavaScript, functions are defined with the function keyword, followed by a name, followed by parentheses. Function names can contain letters, digits, underscores, and dollar signs. The parentheses may include parameter names separated by commas. The code to be executed, by the function, is placed inside curly brackets: `{}`.

`function name(parameter1, parameter2){executable code}`  

Function parameters are listed inside the parentheses () in the function definition.  
Function arguments are the values received by the function when it is invoked.  
Inside the function, the parameters behave as local variables.

The code inside the function is executed when something invokes or calls the function. Functions can be invoked multiple ways:

- Event trigger (user action)
- Invoked by JavaScript code
- Automatically (self invoked)

When JavaScript reaches a return statement, the function will stop executing. If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement. Functions often compute a return value. The return value is returned back to the caller. Functions are very useful because once created, they can be used repeatedly with different arguments to produce different results.
