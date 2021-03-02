# study-guide

## Table of Contents 
* [JavaScript](#JavaScript)
* [JavaScript_Algorithms_DataStructures](#JavaScript_Algorithms_DataStructures)
* [Features_of_JavaScript](#Features_of_JavaScript)
* [Strings_StringMethods](#Strings_StringMethods)
* [Arrays](#Arrays)
* [Objects](#Objects)
* [Functions](#Functions)
* [Conditional_Logic](#Conditional_Logic)
* [TypeScript](#TypeScript)
* [Features_of_TypeScript](#Features_of_TypeScript)
* [React](#react)
* [Features_of_React](#Features_of_React)
* [big0_notation](#big0_notation)
* [Golang](#Golang)
* [Features_of_Golang](#Features_of_Golang)


## JavaScript

What is JavaScript - 
* JavaScript is a client-side and server-side scripting language
* JavaScript can be inserted into HTML pages and is understood by the browser 
* Uses object oriented programming language (OOP)

What are JavaScript data types?
* 8 total data types in JavaScript
* JavaScript has typed values, not typed variables, the following built in types are available:
* Number
* String
* Boolean (true/false)
* Undefined (has not been initialized)
* Null (something is currently unavailable)
* Object (containers for named values called properties or methods)
* Symbol (identifier for object property)
* Bigint 

JavaScript Loops - 
* Execute a block for code a number of times
* for (statement 1 ; statement 2; statement 3) {
    //code block goes here
    //statement 1 = executed one time before execution of code block
    //statement 2 = defines conditions 
    //statement 3 = executed every time after the the code block has been executed 
}
* Help with writing redundant code 

JavaScript if Statement - 
    * Use the if statement to specify a block of JavaScript code to be executed if a condition is true
    * if (condition) {
  //  block of code to be executed if the condition is true
}
    * Use the else statement to specify if a block of code to be executed if the condition is false

JavaScript Arrays - 
* An object that holds values (of any type) 
* Used to store multiple values in one single variable
* Arrays use numbers to access the element in a given array
* You can have objects in arrays, functions in arrays, and arrays in arrays

JavaScript Objects - 
* Objects are variables that contain many values
* var car = {type: 'ford', model: 'f150', color: 'blue'};
* JavaScript objects are containers for named values called properties or methods 

JavaScript Best Practices - 
* Avoid global variables, can be overwritten (use local variables instead)
* Proper indentation and commenting when appropriate 
* Be aware of JavaScript type conversion 
    * JavaScript variables can be converted to a new variable and another data type
    * By the use of a JavaScript function
    * Automatically by JavaScript itself
* Use === Comparison
    * The == always converts (to matching types) before comparison (abstract equality operator)
    * The === operator forces comparison of values and types (strict equality operator)
    
What is "typeof" operator - 
* JavaScript provides a typeof operator that can examine a value and tell you what type it is

What is Scope in JavaScript - 
* Scope determines the accessibility of variables
* Each function has its own scope
* Only code inside that function can access that functions scoped variables
* Two types of scope in JavaScript, local scope and global scope 

## JavaScript_Algorithms_DataStructures

JavaScript Algorithms -
* Functions that transforms certain input data structure into certain output data structure 

Variables - 
* Allow computers to store and manipulate data in a dynamic fashion
* All 8 data types can be stored in variables
* Variables can store different values at different times
* When JavaScript variables are declared, they have an initial value of undefined

Number - 
* Number is a data type in JavaScript that represents numeric data

JavaScript Operators - 
* Assignment operator (=) assigns a value to a variable and allows you to store a value
* Can initialize a variable to an initial value in the same line as it is declared (var myVar = 0)
* Addition (+), Subtraction (-), Multiplication (*), Division (/)
* Easily increment or add one to a variable with ++ operator (i++ equals i = i + 1) and eliminates need for equal sign assignment operator
* Easily decrement or subtract one with -- operator (i-- equals i = i - 1) and eliminates the need for equal sign
* Remainder operator (%) gives the remainder of the division of two numbers
    * Number is checked to be even or odd by seeing the remainder of the division of the number by 2
    * 17 % 2 = 1 (17 is odd)
    * 48 % 2 = (48 is even)

Compound Assignment - 
* Mathematical operation and assignment in one step ( += , -= , *= , /= )
* var myVar = 1;       myVar += 5;      returns 6

Equality Operator - 
* All comparison operators in JavaScript return boolean true or false
* Equality operator (==) compares two values and returns true if equivalent or false if they are not
* Attempts to convert both values being compared to a common type

Strict Equality Operator - 
* Strict equality (===) returns true or false
* Does not perform a type conversion
* If the values being compared have different types, they are considered unequal, and the strict equality operator will return false

Inequality Operator - 
* (!=) opposite of equality operator
* Mean not equal and returns false when equality would return true and vice versa
* Inequality operator will convert data types of values while comparing

Strict Inequality Operator - 
* (!==) means strictly not equal and returns false where strict equality would return true and vice versa
* Will not convert data types


## Features_of_JavaScript

* Lightweight scripting language
* Dynamic typing
* Object-oriented programming language (OOP)
* Functional style

## Strings_StringMethods

Strings are useful for holding data represented in text form
Used for storing and minipulating text
String methods & properties help you work with strings
String values are immutable, and cannot e altered once created

Length - 
* length method returns the length of a string
* var name = "Dana"
* var solution = name.length = 4

Finding a string in a string - 
* indexOf()
* var string = "Hello, nice to meet you"
* var position = string.indexOf("nice") = 7

Split - 
* Splits a string into an array of substrings
* var string = "abcdcba"
* var str = string.split('') =  ['a', 'b', 'c', 'd', 'c', 'b', 'a']

## Arrays 

Can nest arrays within arrays (mulit-dimensional array)

Access array data with indexes -
* Bracket notation that specifies a entry in the array

Manipulate Array Data - 
* Easy way to append data to the end of an array via .push()
    * Takes one or more parameters and pushes them to the end of an array
* .pop() is used to pop a value off the end of an array, removes the last element and returns that element
* .shift() removes the first element in an array
* .unshift() works like .push but adds element at beginning of the array

## Objects

* Use indexes to access and modify data
* Access data in objects through properties
* Useful for storing data in a structrued way
* Two ways to access properties of an object
    * Dot notation 
    * Bracket notation
* Can update and add new data to objects through dot and bracket notation
* Can be thought of as key/value storage 

## Functions 

Function parameters are values that are input or passed into a function when it is called known as arguments

Global Scope & Functions - 
* Scope refers to visibility of variables
* Variables defined outside of a function block have global scope
    * Can be seen everywhere in JS code

Local Scope & Functions - 
* Variables declared within a function as well a function parameters have local scope
    * Only visible within given function

Global vs. Local Scope - 
* Possible to have both local and global variables with same name
* Local variables in this instance will have precedence over global variables

Returning Values - 
* Return statements in functions send a value back out of a function
* If function does not have return statement, when you call the function the inner code is processed but the returned value is undefined
* Can take the return value of a function and assign it to a variable

## Conditional_Logic

If Statements - 
* Used to make decisions in code
* When condition evaluates to true, program executes statement inside curly bracket
* When boolean condition is evaluates to false the statement inside the curly bracket evaluates to false
* 
if (condition is true) {
  statement is executed
}

* With an else statement an alternate block of code can be exectued

Else if - 
* Have multiple conditions that need to be addressed, can chain if statements together with else if statements
* Function is executed from top to bottom

Switch Statements - 
* If you have many options to choose from use a switch statement 
* Tests a value and can have case statements which define various possible values 
* Statements execute from the first matched case value until a break is encoutered 
* Case values are tested wtih (===) strict equality
* Break tells JS to stop execution, if left out it will move to the next statement 
* Default statement should be last
* If the break statement is omitted from a switch statement's case, case statements are executed until a break is encountered
switch (num) {
  case value1:
    statement1;
    break;
  case value2:
    statement2;
    break;
...
  default:
    defaultStatement;
    break;
}


## TypeScript

What is TyepScript - 
* Programming language that is a superset of JavaScript that compiles to plain JavaScript
* TypeScript helps developers catch common errors through a type system and make JavaScript development more efficient
* Uses class-based object-oriented programming 

Do we need to compile TypeScript files and why - 
* Yes, TypeScript is a language extension browsers cant understand
* Converting from TypeScript to JavaScript is called compiling 

What is an interface - 
* Interface is used for type-checking purposes
* Defining an interface means any object must be an object containing interface properties

Built in data types - 
* Number
* String
* Boolean
* Null
* Void
* Undefined

TypeScript object oriented supported terms - 
* Modules
* Classes
* Interfaces
* Inheritance
* Data Types


## Features_of_TypeScript 

* Object-oriented language
* JavaScript is TypeScript
* DOM Manipulation
* TypeScript is just JavaScript


## React

What is react -
* Front-end JavaScript library used for building component based user interfaces 
* Components allow for reusable code
* Created by developers at Facebook 

How does react work - 
* React works by creating a virtual DOM
* When state changes in a component, react identifies what has changed in the virtual DOM, next react updates the DOM with the changes 

What is virtual DOM - 
* Memory representation of the real DOM
* Step that happens between the render function being called and the displaying of elements on the screen
* Entire process is called reconciliation

What are props in React - 
* Props are inputs to a react component
* Props contain data that is passed from a parent component to a child component

Advantages of using React - 
* Increased performance with virtual DOM
* JSX makes code easy to read and write
* Renders on both client and server side
* Easy to integrate with other frameworks

React Comments - 
*  {/* single-line comments */}

React Inline Styles - 
* <div style={{ height: 10 }}>
    
Class Component vs. Functional Component - 
* Class components allow you to use local state and lifecycle hooks
* Functional components are stateless components 

Where in react component should you make a axios request - 
* 'componentDidMount' is where axios requests should be made
* This is executed when the component "mounts" or is added to the DOM for the first time

State - 
* State is a data structure that starts 
* Desribing the current values of a mutable object (mutabe can be changed)
* For example a shopping cart, for any given time it can have a different amount in it 

State Hooks - 
* Allow you to use state without a class component 

Redux - 
* Redux is another way to manage state


## Features_of_React 

JSX - 
* Syntax extension of JavaScript 
* Used with react to describe what the user interface (UI) should look like 
* Allows us to write HTML in files that contain JavaScript code 
    
Components - 
* Building blocks of react applications
* Independent and reusable parts of code that can be process separately
    
Virtual DOM - 
 * React creates a virtual DOM 
 * Virtual DOM is abstraction of the HTML DOM
 * React creates a simplified copy of the HTML DOM
 * No large difference between regular DOM and virtual DOM
    * This is why JSX looks almost like pure HTML
    
One-way-data-binding - 
* Follows unidirectional data flow or data binding
    
High performance - 
* React updates components that have changed, as opposed to updating all components. This makes for faster and efficient web applications


## Golang

What is Golang (Go) - 
* Strong and statically typed programming language
* Used for programming across large-scale network servers 


## Features_of_Golang

* Go is simplistic
* Fast compile times
* Garbage collected language
    * Automatic memory management 
    * Means developer does not need to perform manual memory management
* Built-in concurrency 
* Compiles to a standalone library/binaries 






  
  
 
 
 
 





