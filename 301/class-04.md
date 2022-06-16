# **React and Forms**

## **React Docs - Forms**

### What is a ‘Controlled Component’?

A controlled component is a form that is configured so that the component that renders it also controls what happens in it following any user input.

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?

As long as you can constantly keep the state up to date with the user input by using something like onChange, then I think you should update state upon data entry. This gives you the option to use that state data somewhere else in the same form either before or on submission of the form. This would be impossible if you hadn't already stored the data in state upon entry.

### How do we target what the user is entering if we have an event handler on an input field?

You can target the user input using `event.target.value`.

## **The Conditional (Ternary) Operator Explained**

### Why would we use a ternary operator?

The ternary operator allows you to shorten an if statement to one simple line of code.

### Rewrite the following statement using a ternary statement

```JS
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

```JS
x===y ? console.log(true) : console.log(false)
```

## **Things I want to know more about**

I want to understand controlled components better. It sounds like using controlled components allows you to do a lot of cool stuff in React and I look forward to learning how to properly implement them in my code.
