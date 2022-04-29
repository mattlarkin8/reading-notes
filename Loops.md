# **Operators and Loops**

## **Operators**

There are many different operators in JavaScript and they all do something different.

- Assignment operators
- Comparison operators
- Arithmetic operators
- Bitwise operators
- Logical operators
- String operators
- Conditional operator
- Comma operator
- Unary operators
- Relational operators

### **Assignment Operators**

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is `=`, which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

If a variable refers to an object, then the left-hand side of an assignment expression may make assignments to properties of that variable.

### **Comparison Operators**

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

### **Arithmetic Operators**

An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are `+` `-` `*` `/`. These operators work the same as you would normally use them with a calculator.

### **Bitwise Operators**

A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.

### **Logical Operators**

Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the `&&` and `||` operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value.

### **String Operators**

In addition to the comparison operators, which can be used on string values, the concatenation operator
`+` concatenates two string values together, returning another string that is the union of the two operand strings.

```JS
let username = Jim
alert("Hello" + username); //This sends a browser message saying "Hello Jim".
```

### **Conditional Operator**

The conditional operator is the only JavaScript operator that takes three operands. The operator can have one of two values based on a condition. If the condition is true, the operator has the value of val1. Otherwise it has the value of val2. You can use the conditional operator anywhere you would use a standard operator.

`condition ? val1 : val2`

### **Comma Operator**

The comma operator `,` evaluates both of its operands and returns the value of the last operand. This operator is primarily used inside a for loop, to allow multiple variables to be updated each time through the loop. It is regarded bad style to use it elsewhere, when it is not necessary. Often two separate statements can and should be used instead.

### **Unary Operators**

A unary operation is an operation with only one operand. A very simple example is using `delete`.

`delete object.property;`

### **Relational Operators**

A relational operator compares its operands and returns a Boolean value based on whether the comparison is true.

The `in` operator returns true if the specified property is in the specified object.

`propNameOrNumber in objectName`

Where `propNameOrNumber` is a string, numeric, or symbol expression representing a property name or array index, and `objectName` is the name of an object.

## **Loops**

Loops offer a quick and easy way to do something repeatedly. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times.

### **For Statement**

A `for` loop repeats until a specified condition evaluates to false.

```JS
for ([initialExpression]; [conditionExpression]; [incrementExpression])`
    statement
```

The following steps occur when you execute a for loop:

1. The initializing expression `initialExpression`, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The `conditionExpression` expression is evaluated. If the value of `conditionExpression` is true, the loop statements execute. Otherwise, the `for` loop terminates. If the `conditionExpression` expression is omitted entirely, the condition is assumed to be true.
3. The `statement` executes. Multiple statements can be executed by using a block statement to group them.
4. If present, the update expression `incrementExpression` is executed.
5. Control returns to Step 2.

### **While Statement**

A `while` statement executes its statements as long as a specified condition evaluates to `true`.

```JS
while (condition)
  statement
```

If the `condition` becomes `false`, `statement` within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before `statement` in the loop is executed. If the condition returns `true`, `statement` is executed and the `condition` is tested again. If the condition returns `false`, execution stops, and control is passed to the statement following `while`. 

Multiple statements can be executed by using a block statement to group them.

### **Do-While Statement**

The `do-while` statement repeats until a specified condition evaluates to false.

```JS
do
    statement
while (condition);
```

`statement` is always executed once before the condition is checked.

If `condition` is `true`, the `statement` executes again. At the end of every execution, the `condition` is checked. When the `condition` is `false`, execution stops, and control passes to the statement following `do...while`.

### **Break Statement**

Use the `break` statement to terminate a loop, switch, or in conjunction with a labeled statement.

- When you use `break` without a label, it terminates the innermost enclosing `while`, `do-while`, `for`, or `switch` immediately and transfers control to the following statement.
- When you use `break` with a label, it terminates the specified labeled statement.

`break;`
`break [label];`

<br/>
<br/>
Return to [README](README.md).
