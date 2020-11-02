
### [Table of Contents](https://wondwosentsige.github.io/code-201-reading-notes/Home)

## Class 06 reading notes

### Understanding the problem domain

- Understanding the problem domain is the hardest part of programming.

- Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.

- As developers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

- It is very difficult to solve a problem before you know the question.  *It’s like buzzing in on Jeopardy before you hear the clue and shouting out random questions.*

#### What can you do about it?

- If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

    1. __Make the problem domain easier__
    2. __Get better at understanding the problem domain__

- __You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.__ i.e *that it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.*

- Games are really good at this.  Look at most games today and you’ll find that you start with a very small problem domain.  The first level is usually a tutorial that has a basic set of things you can do so that you don’t get overwhelmed.  But, as you advance through the levels, you usually find they get harder and introduce new concepts that build gradually on what you know, until you understand a pretty large problem domain.

- The other choice is to become better at understanding problem domains.  As developers, we tend to think that sitting down and talking to customers or business people who know about the problem domain is a waste of time. *It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it.*  Best to resist the temptation to “not waste anymore time talking” and make sure you understand a problem inside and out before you try and solve it with code.  *It is much more expensive and time consuming to do things over than it is to do them right the first time.*

- refrence: - "Understanding The Problem Domain Is The Hardest Part Of Programming" by John Sonmez

<a href="https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming
">understanding-the-problem-domain-is-the-hardest-part-of-programming by John Sonmez</a>

### Object Literals

- __Objects group together a set of variables and functions to create a model of a something you would recognize from the real world.__ In an object,variables and functions take on new names.

- __IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES.__ *If a variable is part of an object, it is called a property.* Properties te ll us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms.

- __IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS.__  *If a function is part of an object, it is called a method.* Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.

- Like variables and named functions, properties and methods have a name and a value. In an object, that name is called __a key__.

- *An object cannot have two keys with the same name.* This is because keys are used to access their corresponding values.

- The value of a property can be a st ring, number, Boolean, array, or even another object. __The value of a method is always a function.__

- Programmers use a lot of name/value pairs:
    - HTML uses attribute names and values.
    - CSS uses property names and values.

- In JavaScript:
    - Variables have a name and you can assign them a value of a string, number, or Boolean.
    - Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)
    - Named functions have a name and value that is a set of statements to run if the function is called.
    - Objects consist of a set of name/value pairs (but the names are referred to as keys).

- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.

- Arrays and objects can be used to create complex data sets (and both can contain the other).

### Document Object Model

- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

- *The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:*

1.  MAKING A MODEL OF THE HTML PAGE

    - When the browser loads a web page, it creates a model of the page in memory.
    - __The DOM specifies the way in which the browser should structure this model using a DOM tree.__
    - The DOM is called an object model because the model (the DOM tree) is made of objects. Each object represents a different part of the page loaded in the browser window.

2. ACCESSING AND CHANGING THE HTML PAGE

    - The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.
    - You will hear people call the DOM an __Application Programming Interface (API).__ *User interfaces let humans interact withprograms; APls let programs (and scripts) talk to each other.* The DOM states what your script can "ask the browser about the current page, and how to tell the browser to update what is being shown to the user.

- __THE DOM TREE IS A MODEL OF A WEB PAGE__
    - As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory.
    - It consists of four main types of nodes.
        - __THE DOCUMENT NODE:-__ Every element, attribute, and piece of text in the HTML is represented by its own DOM node. At the top of the tree a document node is added; it represents the entire page.
        - When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for all visits to the DOM tree.

    - __ELEMENT NODES:-__  HTML elements describe the structure of an HTML page. To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is why you start by learning methodsthat allow you to access element nodes, before learning to access and alter text or attributes.

    - __ATTRIBUTE NODES:-__ The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.

    - Attribute nodes are not children of the element thar carries them; they are part of that element. Once you access an element, there are specific JavaScript methods and properties to read or change that element's attributes. For example, it is common to change the values of cl ass attributes to trigger new CSS rules that affect their presentation.
   
    - __TEXT NODES:-__ Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node. Text nodes cannot have children. If an element contains text and another child element, the child element is not a child of the text node but rather a child of the containing element. 
    
- *You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.*

- *Whenever a DOM query can return more than one node, it will always return a Node list.*

- *From an element node, you can access and update its content using properties such as textContent and inner HTML or using DOM manipulation techniques. An element node can contain multiple text nodes and child elements that are siblings of each other.*

- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).

- Browsers offer tools for viewing the DOM tree .





























[>> NEXT (class 07 reading)](https://wondwosentsige.github.io/code-201-reading-notes/class-07)


