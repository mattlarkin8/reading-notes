# **FileIO & Exceptions**

## **Read & Write Files in Python**

Most files consist of a Header, Data, and an EOF. The header contains metadata about the contents of the file. The data is obviously whatever content the file contains. The EOF or End Of File is a character that denotes the end of the file.

When working with files, it is important to consider possible complications from the use of different line ending and character encoding standards. Try to keep this in mind to avoid problems before they arise, especially if you know files are coming from machines with different operating systems.

You can access files in Python in a very similar way to how you browse files on your computer. Use the command `open('filepath.ext')` to open the file in Python. Generally, you want to store that file in a variable so that you can easily work with it after opening it. This variable is typically just named file `file = open('filepath.ext')`. After you are done accessing the file, it is important that you close the file `file.close()`.

Once you have accessed the file, you probably want to do something with it. You can use `file.read()` to read the information in the file. Similarly, `file.write(string)` can be used to write whatever string you want to the file. Keep in mind that once a file is opened in write mode, that files content is deleted and it will only contain what you write to it. This means that `.write()` is actually more like an overwrite. Also, if you open a file in write mode and then close it without writing any content, `.write()` actually acts like a delete function.

## **Exceptions in Python**

In Python, an exception error happens whenever code that was syntactically correct results in an error. The last line of the message will tell you what type of exception error occurred. A couple common examples are ZeroDivisionError and TypeError.

You can use the `raise` command to throw an exception error if a certain condition is met. This can be used in combination with `assert` to test if something is true and then raise an AssertionError in the case that the test returns false.

Normally, your code will stop running after it throws an error. This can be an issue for any sizeable program because depending on the size of the error, the rest of the program could continue operating normally. We can use the `try` and `except` block to allow the program to continue running after an error occurs. All the code you want to attempt should go in the `try` block. It will try to run and if there is an error, the code in your `except` block will be run instead. You could make this some other code that runs or you could use the `except` block to log and print the error that occurred. We can also add on the `else` block which will only execute its code if there were no exceptions and the `finally` block that will always run no matter what happens.

This information gives us the tools to start implementing error handling. We can start writing programs that behave differently based on if an error occurs and what type of error it was. We can even start logging and reporting errors within our code. This feels like a big step towards making functional programs that we might see in real-world applications.

## **Things I want to know more about**

I want to work with error handling and continue to learn more about it. I actually enjoy that part of coding because I can consider how a user would use my program and try to child-proof it so that they can't make it do anything I don't want it to do. It's like a fun game of if they are better at breaking the code than I am at writing it.
