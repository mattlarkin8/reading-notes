# **Lists, Control Flow, and Box Models**

## **HTML Lists**

In HTML there are three different types of lists:

- Unordered lists `<ul>`
- Ordered lists `<ol>`
- Definition lists `<dl>`

Unordered lists are similar to the way I listed the items above. The items will appear with bullet points in the list. Each list item is defined using the `<li>` element. Each list item should be placed in its own `<li>` element.

An Ordered list is the same as an Unordered list, except that it uses the `<ol>` element. The items appear in a numbered list instead of bullet points. Each `<li>` should also be entered in the order that you want it to appear in the list. While this is also true for unordered lists, it is a bit more important here because you don't want stuff out of order in your ordered list.(Otherwise what's the point of setting it ordered in the first place?)

Definition lists are a bit different. They use the `<dl>` element for the list, but they don't use `<li>`. They instead have `<dt>` where you put the definition term and `<dd>` is for the definition of that term. This creates a different kind of list where you can set the term and then define it in a separate space.

```HTML
<dl>
  <dt>Unordered List</dt>
  <dd>Uses <ul> and <li> to create an unordered list.</dd>
  <dt>Ordered List</dt>
  <dd>Uses <ol> and <li> to create a numbered list.</dd>
  <dt>Definition List</dt>
  <dd>Uses <dl> start the list. <dt> defines the list term <br/>
    and <dd> is used to provide the definition of that term.</dd>
</dl>
```

## **Arrays**

An array is used to store a related set of values. You do not need to know or specify how many items will be contained in the array. This allows you to create an array and let items get stored as they become necessary and are added. You can declare an array using `let` the same way you would create any other variable.



## **Things I want to know more about**

The reading covered using CSS to center boxes as well as text along with some other new formatting options that I haven't seen before. I am excited to learn more and use these in practical application so that I can get better at styling with CSS.

I look forward to learning more about the `do-while` loop. I already understand the `while` and `for` loops pretty well and enjoy using them. I think this new type of loop will be interesting play with and figure out its uses.
