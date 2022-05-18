# **CSS Layout**

## **Layouts**

There are two primary types of layouts for a web page: Fixed Width and Liquid.

A Fixed Width layout is made by specifying the width (and sometimes height) of your page elements using a fixed unit of measure, most commonly pixels. This means that regardless of screen size, your elements will always have that set width/height. Use this format if you have a reason that you want your elements to remain the same size.

A Liquid layout, as it sounds, is more dynamic. It uses percentages to specify width and height. This means that no matter how big or small the window, the elements are always the same percentage of that window. This is much more flexible code and can be used to accommodate mobile devices. This is the way that design tends to be written in most cases now since that flexible code can present a nice looking page to more people on different devices.

## **Multiple Style Sheets**

You can use multiple style sheets for your website. Some people choose to create separate style sheets and organize them to server one purpose each. You can be as specific as making individual sheets for layout, tables, colors, and fonts. For whatever reason you have multiple pages, you need to somehow apply them all to your page.

The simple way is to use a separate link for each style sheet. In the `<head>`, link each sheet in the correct order. The sheets are read top down, so anything that conflicts with or makes changes to an elements that has been styled by a previous sheet will be overwritten by the current sheet that is being applied. Keep this in mind so that you don't accidentally mess up your styles.

The other way to apply all of your style sheets is to make one style sheet and link that in your webpage. In this style sheet, you will list out the other style sheets that you want to import. Use `@import` to import those sheets like this:

```CSS
@import url("sheet1.css");
@import url("sheet2.css");
@import url("sheet3.css");

body{
  background-color: gray;
}
```

As you can see in the example above, this main style sheet can also contain styling rules along with the imported pages. You could use this to make one main page where you style the whole page and then import sheets that style more specific elements.

## **Things I want to know more about**

I am interested in learning a bit more about CSS frameworks. It seems like it could be a nice tool to use to get some styling really quickly, but I don't know if the result will be worth the time saved. I want to see some practical applications using it to see see if the result is alright or if it would just be better to make your own.