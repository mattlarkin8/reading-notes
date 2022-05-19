# **Forms and JS Events**

## **HTML Forms**

Forms allow you to collect data from users in a number of different ways. The most common is some form of text input for an email, username, or password. Some other ways of submitting data with forms are radio buttons, checkboxes, drop-down boxes, and file upload bars.

The `<form>` element contains everything for you form and requires the `action` attribute. The action attribute contains the URL for the page that will receive the data when the form is submitted. Forms also usually contain a method that is used to dictate how to send the form.

`<input>` can be used to make multiple different form controls. The `type` attribute determines what kind of input is created.

- `type="text"` creates a single line text input
- `type="password"` creates a single line text input, but the characters are blocked out
- `type="radio"` is used to create a list of radio buttons for a user to pick one option
- `type="checkbox"` creates a list of checkboxes where a user can select multiple inputs
- `type="file"` creates a box with a browse button that is used to upload files
- `type="submit"` is used to create the submit button that is used to send the form to the server
- `type="image"` can be used if you want to use an image for the submit button
- `type="hidden"` allows the web page author to create hidden fields to collect other data
- `type="date"` creates an input box for the user to enter a date
- `type="email"` creates a text box that has validation to ensure an email address was entered
- `type="url"` creates a text box that is validated to make sure a URL was entered
- `type="search"` creates a single line text box for search queries

`<textarea>` can be used when you want a multi-line text box for users to enter data.
`<select>` will make a drop down list for the user to choose one option.
`<option>` specifies the words for each item in the drop down list.
`<button>` is used when you want more control over the appearance of your buttons.

## **Events**

Many different events occur and are registered in the browser when you interact with different web pages. These events can then be interpreted and accessed through the DOM to make things happen based on these events.

To trigger JavaScript code in response to an event, you need to tell JavaScript what to watch for and then what to do. This requires you to specify the element node to look at and then indicate what event on that node you want to trigger a response. Finally, you have to state what code should be run when that event occurs.

## **Things I want to know more about**

I really look forward to being able to use forms to collect data from users. I've wanted to make more responsive programs and pages and this feels like what I've been searching for. It gives me the ability to interact with and gather data from the user in many different ways. I want to see some examples of how it is used and then get some practice with it myself.

I'm excited to work with events to make more responsive programs and web pages. It is really cool to start building more responsive web pages with increasing functionality.
