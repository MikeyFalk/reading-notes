# Code 201 Reading Notes Day 7

## Domain Modeling

- Object-oriented model is an entity that stores data in properties and encapsulates bahviors in methods.

- Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

- Practiced a conctructor and initialized properties for epic fail videos featuring corgis and parkour.

- a constructor function is defined with a function expression when the function is called the data is stored in teh `this.` properties so newly created objects can be accessed later

- instantiated - done with the `new` keyword they are initialized by calling the constructor function.

- after they are stored the variables

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

- Model its attributes with a constructor function that defines and initializes properties.

- Model its behaviors with small methods that focus on doing one job well.

- Create instances using the new keyword followed by a call to a constructor function.

- Store the newly created object in a variable so you can access its properties and methods from outside.

- Use the this variable within methods so you can access the object's properties and methods from inside.


## HTML

### Chapter 6: "Tables" (pp. 126 - 145)

- the `<table>` element is used to add tables ot a web page
- a table is drawn out row by row created by the `<tr>` element
- inside each row there are a number of cells represented by the `<td>` element - `<th>` if it is a header
- `rowspan` and `colspan` attributes are used to make the cells of a table span more than one row or column
- for long tables tou can split the table into a `<thead>`, `<tbody>`, and `<tfoot>`



## JS

### Chapter 3:"Funcitons, Methods, and Objects" (pp.106 - 144)

- constructor notation - creating an object
- `new` keyword and `object` is used to create a new object
- after the object is created you can add properties and methods to it using dot notation.
- should end in a semicolon `;`
- to create an empty object using literal notation use `var hotel = {}`
- curly brackets create an empty object
- to update the value of properties, use dot notation or square brackets.
- use `delete` keyword to remove a property
- to clear the values in a property use can set it to a blank string `hotel.name = ''`
- object constructors can use a function as a template for creating objects
    - frist create a the template with the object's properties and methods
    - name of cinstructor function is a capital letter unlike other functions
    - `+=` adds content to an existing variable

Ways to create objects both can be done with literal notation or object constructor notation:
1. create the object then add properties and methods
2. create the object with properties and methods 

- Browsers have built in objects to tell you width of browser window length of text a user entered into a form field etc.

- they contain 3 things 
    1. Browser Object Model - browser history and device screen
    2. Document Object Model - uses objects to create a representation of the current page
    3. Global Javascript Objects - dates and times

object model is a group of objects that represent related things from the real world

JavaScript has 6 data types
primitive
1. string
2. number
3. Boolean
4. undefined
5. null
and complex
6. object


[<-- Back](README.md)