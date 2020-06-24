[Home](https://sayefdeen.github.io/reading-notes/home)

# Read07

## 1. Introduction

You can use javascript to select any element,attribute,or text from an HTML page, java script allows you to make weeb pages more interactince by accessing and modifying the content by adding element, attribute, and text or remove them form HTML file.

Examples on javascript using :

- SlideShows
- Forms
- Reload part of the page
- Filtering data.

Ok, so what is a script??

A script is a series of instructions that a computer can follow to achieve a goal, scripts are mage up of instructions a computer can follow step-by-step, a browser may use a different parts of the script depending in how the user interacts with the web page, scripts can run different sections of the code in response to the situation areound them, when you are writing a script you vahe to think about.

- Define the goal
- Design the script
- Code each step

## 2. Expression

An expression evaluates into (result in) a single value, broadly speaking there are two types of expressions

- Expressions that just assign a value to a viriable.

  - `var x = 5`
  - `var color = 'red'`
  - `var isReady = true`

- Expressions that user two or more values to return a single value. you can perform any type of operatores in numbers
  - `var area = 3 * 2`

Operators:

- Assignment Opereators : assigne a value to a viriable `color = 'red'`
- Arithmetic Opereators : perform basic math `area = 3 * 2`
- String Opereators : combine two strings `greeting = 'Hi ' + ' Molly '`
- Comparison Opereators : compare two values and return true or false `buy = 3 > 5`
- Logical Opereators : combine expressions and return true or false
  `buy = (3 > 5) && (2 < 4)`

## 3. Functions.

functions lets you group a series of statments together to perform a specific task, if different parts of a script repeal the same task, tou can reuse the function (rather than repeating the same set of statments).

Declaring a function :

`function sayHello() {`
`document.write('Hello!');`
`}`

Calling a function :

`sayHello();`

Declaring a function that needs information:

`function getArea(width,height){`
`return width * height`
`}`

`getArea(2,3)` this will return as 6

`function getArea(width,height){`
`var area = width * height`
`return area`
`}`

`var wallOne = getArea(2,3)`
`var wallTwo = getArea(5,3)`
