# ~~Readings : Problem Domain, Objects, and the DOM.~~

***WHAT IS AN OBJECT?***
***Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. ***

* ***IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES If a variable is part of an object, it is called a property. Properties tell us about the object, such as*** 
***the name of a hotel or the number of rooms it has.Each individual hotel might have a different name and a different number of rooms.***

* ***IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS If a function is part of an object, it is called a method. Methods represent tasks that are associated with*** 
***the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.***

# the DOM : THE DOM TREE IS A MODEL OF A WEB PAGE :
***As a browser loads a web page, it creates a model of that page. 
The model is called a DOM tree, and it is stored in the browsers' memory. 
It consists of four main types of nodes :
BODY OF HTML PAGE***
<html> 
<body> 
<di v id="page"> 
<hl id="header">List</hl> 
<h2>Buy groceries</h2> 
<ul > 
<li id="" class=""><em></em></li> 
<li id="" class=""></l i> 
<l i id="" class=""></l i > 
<l i id=""></l i> 
</ ul > 
<script src="js/l i st.js "></scri pt> 
</ div> 
</ body> 
</ html > 

***1.THE DOCUMENT NODE :
When you access any element, attribute, or text 
node, you navigate to it via the document node. It is 
the starting point for all visits to the DOM tree.***

***2.ELEMENT NODES :
HTML elements describe the structure of an HTML 
page. The-<-hl> - <-h6> elements describe what 
parts are headings; the <-p-> tags indicate where 
paragraphs of text start and finish.
To access the DOM tree, you start by looking for 
elements. Once you find the element you want, then 
you can access its text and attribute nodes if you 
want to. This is why you start by learning methods 
that allow you to access element nodes, before 
learning to access and alter text or attributes.***

***3.ATTRIBUTE NODES  
Attribute nodes are not children of the element that 
carries them; they are part of that element. Once 
you access an element, there are specific JavaScript 
methods and properties to read or change that 
element's attributes. For example, it is common to 
change the values of cl ass attributes to trigger new 
CSS rules that affect their presentation.***

***4.TEXT NODES 
Text nodes cannot have children. If an element 
contains text and another child element, the child 
element is not a child of the text node but rather 
a child of the containing element. (See the <-em> 
element on the first <-i> item. This illustrates how 
the text node is always a new branch of the DOM 
tree, and no further branches come off of it. 

# WORKING WITH THE DOM TREE 
***Accessing and updating the DOM tree involves two steps: 
1: Locate the node that represents the element you want to work with. 
2: Use its text content, child elements, and attributes.*** 

### summary :
***1.the browser represents the page using a DOM tree. 
2.DOM trees have four types of nodes: document nodes, 
element nodes, attribute nodes, and text nodes. 
3.You can select element nodes by their id or cl ass 
attributes, by tag name, or using CSS selector syntax. 
4.Whenever a DOM query can return more than one 
node, it will always return a Nadel list. 
5.From an element node, you can access and update its 
content using properties such as textContent and 
innerHTML or using DOM manipulation techniques. 
6.An element node can contain multiple text nodes and 
child elements that are siblings of each other.*** 
