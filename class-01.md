
### [Table of Contents](https://wondwosentsige.github.io/code-201-reading-notes/Home)

## Class 01 reading notes

### Intoductory HTML and and JavaScript

### HTML

- Understanding HTML and CSS can help anyone who works with the web; designers can create more attractive and usable sites, website editors can create better content, marketers can communicate with their audience more effectively, and managers can commission better sites and get the best out of their teams.

- All websites ude HTML and CSS

- When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.

#### HTML structure

- In order to learn how to write web pages, it is very important to understand how to structure documents.

- HTML uses __elements__ to describes the structure of web pages

- HTML elements are usually made up of two tags: an *_opening tag _* and a *_closing tag._* (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.

- Tags act like containers. They tell you something about the information that lies between their opening and closing tags.

    - The opening <html> tag indicates that anything between it and a closing </html> tag is HTML code.
    - The <body> tag indicates that anything between it and the closing </body> tag should be shown inside the main browser window.
    - The contents of the <title> element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow youto view multiple pages at the same time).
    - Words between <h1> and </h1> are a main heading.
    - A paragraph of text appears between these <p> and </p> tags.

- Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a __name__ and a __value__, separated by an equals sign.

- In the example below, an attribute called *lang* is used to indicate the language used in this element. The value of this attribute on this page specifies it is in "US English".

    - &lt<p lang="en-us">Paragraph in English</p>

### Extra Markup

- Because there have been several versions of HTML, each web page should begin with a __DOCTYPE__ declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included).

- If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
    
    - <!-- comment goes here -->

- Every HTML element can carry the __id attribute__. *It is used to uniquely identify that element from other elements on the page.* Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).

- The id attribute is known as __a global attribute__ because it can be used on any element.

- Every HTML element can also carry __a class attribute__. *Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page.* For example, you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites. To do this you can use the class attribute. Its value should describe the class it belongs to.

- By default, using these attributes does not affect the presentation of an element. It will only change their appearance if there is a CSS rule that indicates it should be displayed differently.

- Some elements will always appear to start on a new line in the browser window. These are known as __block level elements__. Examples of block elements are <h1>, <p>, <ul>, and <li>.

- Some elements will always appear to continue on the same line as their neighbouring elements. These are known as __inline elements__. Examples of inline elements are <a>, <b>, <em>, and <img>.

- The __<div>__ *element allows you to group a set of elements together in one block-level box*. For example, you might createa <div> element to contain all of the elements for the header of your site (the logo and the navigation), or you might create a <div> element to contain comments from visitors.

- In a browser, the contents of the <div> element will start on a new line, but other than this it will make no difference to the presentation of the page.

- Using an id or class attribute on the <div> element, however, means that you can create CSS style rules to indicate how much space the <div> element should occupy on the screen and change the appearance of all the elements contained within it. It can also make it easier to follow your code if you have used <div> elements to hold each section of the page.

- Since there may be several other elements inside a <div> element, it can be helpful to add a comment after the closing </div> tag.

- The __&lt;span&gt;__ *element acts like an inline equivalent of the <div> element*. It is used to either:
    1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
    2. Contain a number of inline elements

- The most common reason why people use <span> elements is so that they can control the appearance of the content of these elements using CSS.

- You will usually see that a class or id attribute is used with <span> elements:

    - To explain the purpose of this <span> element
    - So that CSS styles can be applied to elements that have specific values for these attributes

- There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.)

- Therefore, if you want these characters to appear on your page you need to use what are termed __"escape" characters__ (*also known as escape codes or entity references*). For example, to write a left angled bracket, you can use either &lt; or &#60;. For an ampersand, you can use either &amp; or &#38;.

- You can visit the following website for a complete list of escape characters <a href="https://www.freeformatter.com/html-entities.html">Visit FREEFORMATTER.com!</a>

- 















[>> NEXT (class 02 reading)](https://wondwosentsige.github.io/code-201-reading-notes/class-02)


