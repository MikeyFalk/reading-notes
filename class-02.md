# Code 201 Reading Notes Day 2

## HTML Chapter 2: "Text" (pp 40 - 61)

    * Headings and paragraphs
    * Bold, italic, emphasis
    
    * Structural and semantic markup
    * HTML elements are used to describe the structure of the page (i.e. headings, sub-headings, paragraphs)
    * They also provide smeantic info (i.e. where emphasis should be placed, the definitions of any acronymism used, when given text is a quotation)

## HTML Chapter 10: "Introducing CSS" (pp 226 - 245)

    * What CSS does
    * How CSS works
    * Rules, properties, and values
    
    * CSS treats each HTML element as if it appears inside  is own boox and uses rules to indicate how that element should look
    * Rules are made up of ** selectors ** - specify the elements the rule applies to ** declarations ** t- indicate what these elemetns should look like
    * Different types of selectors allow you to target your rules at different elements
    * Declarations are made up of 2 parts
        1. Properties - the `font-family` property sets the choice of font
        2. values - `arial` specifies Arial as the preffered typeface
    * CSS rules usually appear in a seperate document although they may appear within an HTML page

## JS Chapter 2: "Basic Java Script Instructions" (pp 53 -84)

    * The Langauge: Syntax and Grammar
    * Giving Instructions: For a Browser to Follow
    
    * Script is made up of a series of statements - like a setp in a recipe
    * Scripts are precise instructions 
    * Variables are used to temporarily store pieces of information for the script
    * Arrays are special types of variables that store more than one piece of related information
    * JS distinguishes between numbers, strings, and boolena values
    * Expressions evaluate into a single value
    * Expressions rely on operators to calculate a value

## JS Chapter 4: "Decisions and Loops" (pp 145 - 162)

    * How to control the flow of data in scripts to handle different situations
    * Evaluations
    * Decisions
    * Loops
    
    * Conditional statements allow code to make decisions on what to do next
    * Comparison operators (`===`. `!==`, `==`, `!=`, `<`, `>`, `<=`, `=>`)are used to compare two operands
    * Logical operators allow you to combine more than one set of comparison operators
    * if...else statements allow you to run one set of code if a condition is true and another if it is false
    * switch statements allow you to compare a value against a possible outcomes and provide a default option is none match

    ## Additional Resources

        * https://chris.beams.io/posts/git-commit/
        * when adding git commit messages try to be concise and consistent
        * It takes work and practice
        * Commits messages need to communicate context (why) about a change
        * You can use a diff to understand what changed
        * Commit messages can show if a developer is a good collaborator
        * Good commit logs make a project more maintainable

        * 7 Rules to a great git commit message
               1. Separate subject from body with a blank line
                2. Limit the subject line to 50 characters
                3. Capitalize the subject line
                4. Do not end the subject line with a period
                5. Use the imperative mood in the subject line
                6. Wrap the body at 72 characters
                7. Use the body to explain what and why vs. how
        
        * Remember to read this when I have time - https://git-scm.com/book/en/v2

[<-- Back](README.md)