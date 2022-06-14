# **Readings: State and Props**

## **React lifecycle**

### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

In the diagram, render happens first during the render phase. componentDidMount happens later in the commit phase.

### What is the very first thing to happen in the lifecycle of React?

The very first thing that happens is Constructor, which is part of the mounting phase.

### Put the following items in the order that they happen

Constructor, render, React updates, componentDidMount, componentWillUnmount

### What does `componentDidMount` do?

componentDidMount is a method that is invoked immediately when a component is mounted. It can be used to initialize the DOM or initiate network requests. It is good for subscriptions or API calls.

## **React State Vs Props**

### What types of things can you pass in the props?

You can pass in data like you would pass an argument into a function. This could be all sorts of different things depending on what you want to do. This means you could pass in a number as a value for something or you could pass in strings of text for a title and sub-titles.

### What is the big difference between props and state?

Props are passed into a component. State is handled *inside* the component and are updated inside the component. Props are handled *outside* the component and must be updated outside the component.

### When do we re-render our application?

If the state is updated, the application will be re-rendered to reflect those changes.

### What are some examples of things that we could store in state?

State should be used to store anything that you want to be updated and have those updates rendered to the application. This could be any number of things based on what you are building. A good example from the video was storing a counter whose value gets updated and then re-renders the page to reflect the updated count. Another example was storing information from forms. You can store a bunch of different data from the form whenever any of the form inputs are changed.

## **Things I want to know more about**

I am excited to learn more about state. Being able to store and update data within the component and then re-render the application with those changes sounds like a really cool feature. I think this is going to be a big part of our work in the future and I want to get some practice using it in a real application.
