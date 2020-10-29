
### [Table of Contents](https://wondwosentsige.github.io/code-201-reading-notes/Home)

## Class 04 reading notes

### HTML Links

- __Links__ are *the defining feature of the web because they allow you to move from one web page to another* — enabling the very idea of browsing or surfing.

- We will commonly come across the following types of links: 

    - Links from one website to another
    - Links from one page to another on the same website
    - Links from one part of a web page to another part of the same page
    - Links that open in a new browser window
    - Links that start up your email program and address a new email to someone

- Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.

- When you link to a different website, the value of the href attribute will be the full web address for the site, which is
known as an absolute URL. Example <a href="http://www.empireonline.com"> Empire</a>.

- When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.

- If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file. Example: <a href="index.html">Home</a>

- __Relative URLs__ can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files

- To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to. Example : <a href="mailto:jon@example.org">Email Jon</a>

### Layouts

- In HTML, layouts Control the position of elements
- Create site layouts
- Design for different sized screens

- CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

- Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

- If one block-level element sits inside another block-level element then the outer box is known as the __containing or parent element__.

- It is common to group a number of elements together inside a <div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.

- CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

    - __Normal flow:__ Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).

    - __Relative Positioning:__ This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.

    - __Absolute positioning:__ This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.


 ### JavaScript functions, methods and objects

 - Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).
    
- Browsers require very detailed instructions about what we want them to do. Therefore, complex scripts can run to hundreds (even thousands) of lines. *Programmers use functions, methods, and objects to organize their code.*

- Functions consist of a series of statements that have been grouped together because they perform a specific task.

- A method is the same as a function, except methods are created inside (and are part of) an object

### 6 Reasons for Pair Programming

- Pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together

- Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

#### Why pair programming

    1. great efficiency
    2. engaged collaboration
    3. learning from fellow students
    4. social skills
    5. job interview readiness
    6. work environment readiness


























[>> NEXT (class 05 reading)](https://wondwosentsige.github.io/code-201-reading-notes/class-05)


