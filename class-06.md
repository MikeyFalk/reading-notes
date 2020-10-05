# Code 201 Reading Notes Day 6

## Understanding the Problem Domain

- A problem domain is what the developer is trying to solve for. 
- They can be super complicated like a double sided jigsaw puzzle without color
- The represent real world problems so they can be messy 
- They are difficult to solve because they are complex
- When coding for a problem domain is it important to fully understand the problem
- Once we have a full undestanding of the problem coding becomes easier
- Breaking the problem into smaller steps with a singular focus is one way 
- Talking with the client is another way
- Proper planning up front can save time and resources in the long run  

## JS 
### Chapter 3: "Object Literals" (pp.100 - 105)

- Object - group together a set of variables and fucntions to create a model of something you would recognize from the real world.

- In an object functions and variables take on new names

- variables become known as properties 
- functions become kown as methods
- objects are in curly braces

- properties and mehods have a name in an object called a key
- keys have to have a unique name
- value of a property can be a string, number, Boolean, array or another object. 
- The value of a method is always a function

**Literal Notation - easiest and most popular way to create objects**

- The object is the curly braces and the conetent between them 
- The object is stored in a variable with a name 
- each key is seperated from its value by a semicolon 
- each property and method is seperated with a comma except the last value

- strings live in quotes and arrays in brackets

**Dot Notation**
- dot notation - way to access properties and methods of an object
square brackets can also be used.
- to access a property ro method you use the name or object `.` name to of the property or method.

- `'` is called a member operator
property or method on the right is a memeber of the object on the left

**dot notation**
`var hotelName = hotel.name;`
*or*
**square bracket syntax**
`var hotelName = hotel['name'];`

### Chapter 5: "Document Object Model" (pp.183 - 242)

*Document Object Model (DOM) - specifcy how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a page while it is in the browser window.*

- not HTML or JS - seperated set of rules 

- DOM can be called and API application programming interface which let programs and scripts talk to each other

- browser loads a web page and creates a model of the page stored in the browsers memory

- Each Node is an object with methods and properties 

- Scripts access and update this DOM tree not the HTML file 
Any changes made to th DOM tree are reflected in the browser

There are 4 main types of nodes
**Document Node** - starting point for all visits to the DOM tree
**Element Node** - HTML elements that describe the structure of an HTML page
**Attribute Nodes** - The opening tags of HTML elements
**Text Nodes** - you can access the text node after reaching the element nodes within the element

- Working with the DOM tree

**2 steps to working with the DOM tree:**

1. locate the node that represents the element you want to work with

2. use its text content, child elements and attirbutes 

- You can Select element nodes by their id or class attributes, by tag name, or using the CSS selector syntax

- When a DOM query can return more than one node it will return a node list

- From an element node you can access and update its content unsing properties like text content and inner HTML using DOM manipulation techniques

- element nodes can contain multiple text nodes and child elements that are siblings to each other

- older browsers implementation of DOM is inconsistant and the reason we should use jQuery

- Browesers have tools to viewing the DOM tree.

[<-- Back](README.md)