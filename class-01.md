# Code Fellows 201 Pre-work Summaries Notes

## HTML

### Introduction (pp.2-11)

#### Books are set up for 2 types of people

1. those who want to learn building a website from scratch
2. owners of websites who want more control

#### 6 types of pages in the book  

1. **Intorductions** at the beginning of each chapter
2. **Background** to explain context
3. **Example** to demonstrate topics in code
4. **Reference** introduce key pieces of code HTML in blue and CSS in pink
5. **Diagram** infographics provide simple visual refence to topics in the chapter
6. **Summary** remind you of the topics covered in the chapter

#### Languages

- **HTML:** structure and content of the web page
- **CSS:** presentation and layout of the web page.

#### Web Access

1. **Browsers:** ex. firefox. How people access the internet. Browsers intrpret code to display on your screen. Some don't support all features of HTML5 or CSS3 or users can be using an older version. 
2. **Web Servers:** Hosts the website
3. **Devices:** mobile phone, tablet, laptop, desktop etc  
4. **Screen Readers:** access to the internet for visaully impared, driving or jogging

### HTML Chapter 1: “Structure” (pp.12-39)

- Understanding Structure
- learning Markup
- Tags and Elements

1. HTML pages are text documents
2. HTML uses tags (angled brackets) to give meaning to content
3. Tags can be called elements
4. Tags come in pairs
5. Opening tags can carry attributes to tell us more about the content
6. Attributes require a name and a value
7. learning HTML requires learning what tags are available what they do and where they can go.

### HTML Chapter 8: “Extra Markup” (p.176-199)

- specifying differnt versions of HTML
- Identifying and grouping elements
- Comments, meta information and iframes

1. DOCTYPES tell browsers which version of HTML you are using
2. `<!--> and -->` allow a user to comment on code
3. `id` and `class` identify particular elements `id` is a specifically named element `class` is a type of element
4. `<div>` and `<span>` group block level and inline elements together
5. `<iframes>` cut windows into web pages which other pages can be displayed
6. `<meta>` allows coder to supply additional information about a page
7. escape characters are used to include special characters into your page `<`, `>` and `(c)` (c).

### HTML Chapter 17: “HTML5 Layout” (pp.428-451)

- HTML5 layout elements
- How old browsers understand new elements
- Styling HTML5 elements with CSS

1. HTML5 indicates the purpose of different parts of a webpageto help describe the structure
2. new elements are clearer and easier to understand `<section>` vs. `<div/>`
3. Older browsers need to be told which elements are block level.
4. HTML5 needs extra JS (available in Google for free) to make it work in Explorer 8 older version of IE 

### HTML Chapter 18: “Process & Design” (pp.452-475)

- How to approach building a site
- Understanding your audience and their needs
- How to present information to visitors want to see

1. Imprortant to understand target audience. Why are they visiting, what they are lookign for, how often will they visit 
2. Site maps are used to provide structure 
3. Wireframes are useful to organize the information and layout of the page
4. Visual hierarchy hleps communicate what you want to tell visitors
5. use color, size, and style to differentiate between pieces of information.
6. use grouping and similarity to simplify the information you present.

## JS

### Introduction

- JS makes the webpage more interactive
- jQuery makes writting JS much easier

**What JS Does:**

1. Access content
2. Modify content
3. Program rules
4. React to events

**Examples:**

1. Slideshows
2. Forms
3. Reload part of a page
4. Filter Data

### JS Chapter 1: “The ABC of Programming” (pp.11-52)

- What is a script
- How computers fit in with the world around them
- How to write a script for a webpage

 1. A Script is a series of instructions that the computer follows to achieve a goal
 2. Scripts may only use a subset of the instructions
 3. instructions must solve the problem programmatically
 4. to wrtie a script break down your goal into a series of tasks and work out each step needed to complete that task (flowcharts help)

 5. Computers create models of the world using data
 6. object represent physical things have properties that tell us about the object methods that perform the task using the properties and events that are triggered when a user interacts with the computer
 7. programmers us code to say "when this event occurs, run that code"
 web browsers use HTML  markup to create a model of the web page each element creates its own node
 8. to make pages interactive you write code that uses the browsers model of the webpage

 9. JS should go in its own text file. Should have js extension
 10. HTML uses `<script>` element to tell browser to load the JS file `<link>` is used for a CSS file.
 11. Source code for a website doesn't show changes to HTML because JS works with the model of the webpage that the browsers create/ 

 [<-- Back](README.md)