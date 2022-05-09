# **CSS**

### **What is CSS?**

CSS or Cascading Style Sheets is a declarative syntax for defining the presentation of web pages. You can use it to style and format your webpage. There are many different capabilities ranging from editing background or text color to lining up multiple images and text boxes to properly display your information.

### **How to use CSS**

CSS is rule based and works by specifying what styles should be applied to certain elements or groups of elements. When creating your style sheet, you should generally start at the top of the page and work your way down as you configure different elements. For example, if we start at the top of the page with an h1 header, we can write:

```HTML
h1{
color:blue;
font-size:20px;
}
```

This will make your header text blue and set the font size to 20 pixels. It is also very important that you finish each declaration with a `;` to end that declaration. If you don't close each declaration properly then none of them will work because it will be interpreted as one long line of code that doesn't resolve to anything.

### **Implementing CSS in your code**

For this example we will assume that you have an HTML webpage that you want to incorporate CCS styling into. There are three different ways to insert a style sheet.

#### **External CSS**

When using external CSS, you create an individual CSS file where you define all the styling for the entire webpage. You must then link this style sheet to each HTML page where it is going to be used. This link should be in the `<head>` section of the HTML file. Below is an example from an HTML file where a style sheet has been linked.

```HTML
<!DOCTYPE html>
 <html>
 <head>
    <link rel="stylesheet" href="styles.css">
 </head>
```

#### **Internal CSS**

Internal CSS is somewhat similar to External in the way that you create all of the styling for the page upfront and put it in the `<head>` section. What is different, is that instead of linking to an external file, all of the styling commands are written in the `<head>` section and it is all apart of the same HTML file. That would look something like this:

```HTML
<!DOCTYPE html>
 <html>
 <head>
 <style>
 body {
  background-color: grey;
 }

 h1 {
  color: blue;
  font-size: 20px;
 }
 </style>
 </head>
 ```

 As you can see it is contained in it's own `<style>` section, but using this method adds a lot of extra code to the `<head>` section and your file overall. This method could be used if you had only a couple style changes to make or it was unique to one webpage, but the external method can also do the same things and is more neat and organized than Internal CSS.

#### **Inline CSS**

Inline CSS is the most different and least preferred of the three options. It is only used to style one element at a time within the HTML code.

```HTML
 <!DOCTYPE html>
  <html>
  <body>

  <h1 style="color:blue;font-size: 20px;">Heading text.</h1>
  <p style="color:red;">Paragraph text.</p>

  </body>
  </html>
```

You can see here that for each element you want to style, you must define it with an individual style attribute. Multiple styling commands can be in the same line, but they must be separated by a `;`. This method is tedious and also clutters your HTML file, which is why it is not recommended to be used often.

<br />
<br />
Return to [README](README.md).
