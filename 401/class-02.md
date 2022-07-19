# **Testing and Modules**

## **Tests**

Test-Driven Development is interesting to think about because you appear to be working backwards. However, it is going to be a part of the big step to transition from just writing code and trying to solve a problem, to planning things ahead of time and creating a solution before starting to write any of the code. This focus on the planning and design aspect of coding is going to be a big change, but the upfront work will be worth it to setup the ease of implementing a solution with your plan.

## **Modules**

A module is a file with Python definitions and statements and has the .py extension. A Python file can be a standalone program or a reusable module. Depending on the situation, you will want to create one or the other.  Understanding how modules are imported and executed, as well as the `_name_` variable, are important in doing this. Every Python module has a `_name_` variable that changes if it is imported. If a module is run as the main program, then its `_name_` will be "_main_". When a module is imported, its name is set to the modules name. This allows us to use `_name_ == "_main_"` to check whether a module has been imported or not. Using this allows us to make a module run only if it was executed directly.

## **Recursion**

When a process calls itself either directly or indirectly, that is recursion. Recursive functions can be used to shorten code, making it more efficient and readable. In the cases where it is an appropriate solution, a recursive function can solve the same problem way faster that another solution. They are, however, more intensive for memory usage due to adding multiple calls to the stack using LIFO. It is important to remember that a recursive function is very similar to a loop and needs a way to exit the loop so that it doesn't go on infinitely. Direct Recursion is when the function specifically calls itself. If function1 calls function2 and function2 calls function1, that is indirect recursion because it is called by a function other that itself.

## **Things I want to know more about**

I want to learn more about using recursive functions. The concept seems really cool and I'm sure there will be some great ways to implement it to make a solution that is neat and efficient.
