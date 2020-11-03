
### [Table of Contents](https://wondwosentsige.github.io/code-201-reading-notes/Home)

## Class 07 reading notes

### Domain Modelong

- Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

- A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

- *Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.*

Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

2. Model its attributes with a constructor function that defines and initializes properties.

3. Model its behaviors with small methods that focus on doing one job well.

4. Create instances using the new keyword followed by a call to a constructor function.

5. Store the newly created object in a variable so you can access its properties and methods from outside.

6. Use the this variable within methods so you can access the object's properties and methods from inside.


### HTML Tables

- There are several types of information that need to be displayed in a grid or table.

- When representing information in a table, you need to think in terms of a grid made up of rows and columns (a bit like a spreadsheet).

- Each block in the grid is referred to as a table cell. In HTML a table is written out row by row.

- Basic Table Structure

- The <table> element is used to create a table. The contents of the table are written out rowby row.

- By typing <tr> You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.) It is followed by one or more
 elements of <td> (one for each cell in that row). At the end of the row you use a closing </tr> tag.

- With <td> Each cell of a table is represented using a <td> element. (The td stands for table data.) At the end of each cell you use a closing </td> tag. Some browsers automatically draw lines around the table and/or the individual cells.

- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

- For long tables you can split the table into a <thead>, <tbody>, and <tfoot>. as necessary

### Functions, Methods, and Objects

- Functions allow you to group a set of related statements together that represent a single task.

- Functions can take parameters (informatiorJ required to do their job) and may return a value.

- The __new__ keyword and the object constructor create a blank object.

- __To update the value of properties, use dot notation or square brackets__

- Once you have created an object (using literal or constructor notation), you can add new properties to it.*You do this using the dot notation*

- *The keyword __this__ is commonly used inside functions and objects.* Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.

- An object is a series of variables and functions that represent something from the world around you.

- If you want to access items via a property name or key, use an object (but note that each key in the object must be unique). If the order of the items is important, use an array.

- In JavaScript, data is represented using name/value pairs. To organize your data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as a key.

- In an object, variables are known as properties of the object; functions are known as methods of the object.

- Arrays are a special type of object. They hold a related set of key/value pairs (like all objects), but the key for each value is its index number

- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

- Browsers come with a set of __built-in objects__ that represent things like the browser window and the current web page shown in that window. These *built-in objects act like a toolkit for creating interactive web pages.*

- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.

- The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.

- The topmost object in the Document Object Model (or DOM) is the document object. It represents the web page loaded into the current browser window or tab.

- __Arrays and objects__ can be used to create complex data sets (and both can contain the other).

























[>> NEXT (class 08 reading)](https://wondwosentsige.github.io/code-201-reading-notes/class-08)


