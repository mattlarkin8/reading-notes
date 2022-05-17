# **Object-Oriented Programming and HTML Tables**

## **HTML Tables**

A table presents information in a grid format. Each block in the grid is a called table cell. The table is written out row by row.

`<table>` is used to create a table.
`<tr>` starts each row of the table and `</tr>` ends that row.
`<td>` stands for 'table data' and is used for each cell in the table.
`<th>` stands for 'table heading' and is used to give a heading to either a row or column.
`colspan="#ofCells"` and `rowspan="#ofCells"` can be used to make a cell span more than one column or row respectively.

Long tables can be used to create longer and more specific tables.

`<thead>` is used for the headings of the table.
`<tbody>` contains the body of your table.
`<tfoot>` is used for the footer of the table.

This format allows you to have different content in the first and last rows(used for header and footer) to better organize your table.

## **Objects**

You can use constructor notation to create an object like this:

```JS
let objectName = new Object();
objectName.stuff = 'content';
objectName.moreStuff = 'other content';
objectName.otherStuff = aNumber;
objectName.doStuff = function(){
  execute stuff;
};
```

You can also create an object using object literal notation:

```JS
let objectName = {
  stuff: 'content',
  moreStuff: 'other content',
  otherStuff: aNumber,
  doStuff: function(){
    execute stuff;
  },
};
```

Properties can be added and removed from objects by using dot notation.
`delete objectName.property` will delete the specified property.
To add a property, you can just write it into existence: `objectName.newProperty`

Objects can be used to store and manage all different kinds of data. You can even put arrays in objects and objects in arrays. This opens the door for a lot of different data storage solutions as well as different ways to call that data out and use it.

There are some global objects that we are probably familiar with, but didn't realize were objects.

- String
- Number
- Math
- Date and Time

All of these are built in global objects and have many methods and properties that can be used when you have a matching value of that object type.

## **Things I want to know more about**

I think it is somewhat complicated at first glance, but I want to know more about storing arrays in objects and more importantly, storing objects in arrays. This obviously has the potential for a lot of different functionality using data storage and calling things out of arrays and objects.
