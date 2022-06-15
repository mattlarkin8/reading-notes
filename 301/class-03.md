# **Passing Functions as Props**

## **React Docs - lists and keys**

### What does .map() return?

The map function returns a new array that contains each item from the previous array, usually after you've performed some operation on them.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

Loop through the array with your function of choice and return a new array where you've converted the values to your desired element type. You can now put the new array in the element where you want it to display, just make sure you wrap the variable name in curly braces so that it is interpreted correctly.

### Each list item needs a unique ____?

When creating list a list of elements, each item needs to have a unique key attribute.

### What is the purpose of a key?

Keys allow React to monitor changes to items because the key value uniquely identifies each element.

## **The Spread Operator**

### What is the spread operator?

The spread operator is a syntax that allows you to expand iterable objects into lists of arguments.

### List 4 things that the spread operator can do

Spread can copy an array, combine arrays, combine objects, and add to state in React.

### Give an example of using the spread operator to combine two arrays

Spread can combine arrays like this:

```JS
let arr1 = [1,2,3];
let arr2 = [4,5,6];
let addArr = [...arr1,...arr2];
```

This example combines the two arrays into one where the new contents is `[1,2,3,4,5,6]`.

### Give an example of using the spread operator to add a new item to an array

```JS
let nums = [1,2,3];
let moreNums = [...nums,4,5];
//moreNums is now [1,2,3,4,5]
```

This easily adds an array and new items to a new array.

### Give an example of using the spread operator to combine two objects into one

```JS
let obj1 = {test: 1}
let obj2 = {example: 2}
let obj3 = {...obj1,...obj2}
//obj3 now contains{test: 1, example: 2}
```

Similar to the other combining functionality of spread, you can easily add two objects together like this.

## **How to Pass Functions Between Components**

### In the video, what is the first step that the developer does to pass functions between components?

Create a function at the same level as the state you want to change.

### In your own words, what does the increment function do?

The increment function uses conditional logic to find the desired object in an array of objects, update its count, and then update the state of the array to reflect the new count.

### How can you pass a method from a parent component into a child component?

A method can be passed from parent to child through the use of props.

### How does the child component invoke a method that was passed to it from a parent component?

A child component can invoke a passed method by calling it with `this.props.methodName()`.

## **Things I want to know more about**

I want to get practice using Spread. I think it is a really cool tool from the reading and it seems like it will provide a bunch of utility. I'm looking forward to getting better at incorporating tools like this into my code.
