
### [Table of Contents](https://wondwosentsige.github.io/code-201-reading-notes/Home)

## Class 08 reading notes

### CSS layout

- __CSS treats each HTML element as if it is in its own box__. This box will either be a block-level box or an inline box.

- *Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text.* You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

- Block-level elements start on a new line Examples include: <h1> <p> <ul> <li>.

- Inline elements flow in between surrounding text Examples include: <img> <b> <i>.

- If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

- CSS has the following __positioning schemes__ that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

    - __Normal flow__ Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).

    - __Relative Positioning__ This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.

    - __Absolute positioning__ This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

 - *When you use relative, fixed, or absolute positioning, boxes can overlap*. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page.

 - The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

 - *Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.*

 - *Resolution refers to the number of dots a screen shows per inch*. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

 - *Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).*

 - *Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.*

 - CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.

 - *Grids help create professional and flexible designs.*
 
 - CSS Frameworks provide rules for common tasks.

 - *You can include multiple CSS files in one page.*























[>> NEXT (class 09 reading)](https://wondwosentsige.github.io/code-201-reading-notes/class-09)


