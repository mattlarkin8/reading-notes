# **Putting it all together**

## **React Docs - Thinking in React**

### What is the single responsibility principle and how does it apply to components?

A component should do only one thing. If it grows too large, you should deconstruct it into smaller components to maintain this principle.

### What does it mean to build a ‘static’ version of your application?

A static application takes your data and renders the UI, but does not have any interactivity.

### Once you have a static application, what do you need to add?

After you have completed your static application, you can add in the interactive functionality.

### What are the three questions you can ask to determine if something is state?

Is it passed from a parent using props? If yes, then it should **not** be state.  
Does it remain unchanged over time? If yes, it is probably **not** state.  
Can you compute it based on any other state or props in your component? If yes, then its **not** state.

### How can you identify where state needs to live?

Identify all components that render something using that state and then find a common owner component above all those components. This should be where you want to store that state data.

## **Higher-Order Functions**

### What is a “higher-order function”?

A higher-order function operates on other functions, by either returning them or taking them as arguments.

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Line 2 returns a boolean value based on whether or not m is greater than n.

### Explain how either map or reduce operates, with regards to higher-order functions.

Map and reduce both operate as higher functions because of the operations they perform. Although they look simple on the surface, the examples from the reading break it down so you can see the inner workings. They both operate on an array of data which they take as an argument and then return a transformed version of that data after performing another function on it. The function that is performed to transform the data is also passed into map or reduce as another argument along with the data. This reading revealed some of the simple functions we've been using to actually not be so simple.

## **Things I want to know more about**

I would like to get more practice using higher order functions. It looks like you have the ability to perform more complex logical operations by passing and returning functions. I would like to understand this concept better not only to be able to use it, but for the fun of being able to think through the logic of all operations being performed.
