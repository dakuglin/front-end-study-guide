# study-guide

## Table of Contents 
* [JavaScript](#JavaScript)
* [JavaScript_Algorithms_DataStructures](#JavaScript_Algorithms_DataStructures)
* [Features_of_JavaScript](#Features_of_JavaScript)
* [Strings_StringMethods](#Strings_StringMethods)
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
* Execute a block fo code a number of times
* for (statement 1 ; statement 2; statement 3) {
    //code block goes here
    //statement 1 = executed one time before execution of code block
    //statement 2 = defines conditions 
    //statement 3 = executed every time after the the code block has been executed 
}
* Help with writing redundant code 

JavaScript if Statement - 
    * Use the if statement to specify a block of JavaScript code to be exectued if a condition is true
    * if (condition) {
  //  block of code to be executed if the condition is true
}
    * Use the else statement to specify if a block of code to be exectued if the condition is false

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
* Varuables can store different values at different times
* When JavaScript variables are declared, they have an initial value of undefined

Number - 
* Number is a data type in JavaScript that represents numeric data

JavaScript Operators - 
* Assignment operator (=) assigns a value to a variable and allows you to store a value
* Can initalize a variable to an initial value in the same line as it is declared (var myVar = 0)
* Addition (+), Subtraction (-), Multiplication (*), Division (/)
* Easily increment or add one to a variable with ++ operator (i++ equals i = i + 1) and eliminates need for equal sign assignment orperator




## Features_of_JavaScript

* Lightweight scripting language
* Dynamic typing
* Object-oriented programming language (OOP)
* Functional style

## Strings_StringMethods

Strings are useful for holding data represented in text form
Used for storing and minipulating text
String methods & properties help you work with strings

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






  
  
 
 
 
 





