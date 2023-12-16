# Class 02: Introduction to Web Development


## Review

Trying to get high Lighthouse Accesibility scores is very important.

We want to build stuff for everybody.

**Note to self**: Review your HTML tags and functionality. Specially the ones on the boilerplate.

**Note to self**: Know the difference between internal and external CSS style.

**Note to self**: The entire CSS block is known as a CSS declaration / CSS rule.

**Note to self**: The **<script>** tag should be written as ** <script defer> ** if you put it at the bottom of the HTML file.

**Note to self**: We will learn to do something simplier when i comes to string concatenation - **string template literal**.

It is very similar to the F-strings in Python

```
// Template literal

alert(`Hello ${variable_name}, rest of the sentence goes in here.`)
```
**Note to self**: Using single quotes is the standard in Javascript.


# Javascript as a Language

Javascript is considered a loosely typed & dynamic language.

**Loosely typed**: We do not have to know the type of data before declaring a variable.

**Dynamic**: It means that we can change the type of data whenever we want to.

Typescript does not let you change the data type.

## Three data types to focus on

+ Strings - sequence of characters.
+ Numbers - any number
+ Booleans - True or False
+ Undefines - data types that have not been defined.
+ Null 

# IF/ELSE

```
if (condition){
  Do something;
}
```




```
"use strict"; // Put this at the top of your Js program

let hungry = true;
let thirsty = false;


if( I am hungry){
  eat;  //if this is NO, it will go to the next condition
} else if(I am thirsty){ //if it is TRUE, it will drink
  drink;

}
```
// **else** is the only thing that does not count a condition.

# TRUTHY & FALSEY

Wev can use other data types to represent a True or a False value.

//Numbers
// 0 is the only FALSEY value
// Any other number is considered TRUTHY

```

if(1){
  console.log("this is a truthy value)  //Output: this is a truthy value
}
```


//We will not see it in the colsole because it is False.

```
if(0){
  console.log("This is a falsely value")
}
```

# Strings
An empty string is the only falsey value.
Any other string representation is a Truthy value.

# Comparison Operators

// == losely equals.

// === strictly equals - use it to compare things.

// >, < , >== , <==  

// !==  STRICTLY NOT EQUAL - THIS ONE IS THE MOST IMPORTANT

//  != LOSELY NOT EQUAL


```
let a = 10;

console.log(a === 10);  //Output is: True

```

```
let a = 10;

console.log(a === "10");  //Output is: False

```

# Logical Operators

// &&  It represents "AND"  Both things being compared must be True.

// ||  they represent "OR"  Anything being compared must be True

//!   It represents "NOT"   It gives you the opposite of whatever it is in front of.


```
let b = 100;

if(b < 1000  && b > 5){
  console.log("Will this run?)
}

```


```

if(!true){
  console.log("Will this one run?)  //This one will be FALSE. It becomes the opposite.
}

```

//Lab starts at 1hour and 53 minutes.

# Read Class 02: Basics of HTML, CSS, & Javascript



## Q1: Why is it important to use semantic elements in our HTML?
It is important to use semantic HTML so that the browser knows how to display content correctly. It is also known that semantic HTML improves SEO and accessibility.

## Q2: How many levels of headings are there in HTML?
There are six levels of headings in HTML. It starts with H1 and it ends with H6.


## Q3: What are some uses for the **<sup>** and **<sub>** elements 
We will use **superscript** and **subscript** when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. 

**For Example**

```
<p>Jimmy´s birthday is on the 3<sup>th</sup> of January.<p>

```

The <sup> tag will raise the **th** and will put it on top of the number 3.


## Q4: When using the **<abbr>** elements, what attribute must be added to provide the full expansion of the term?


# Learn CSS

## What are ways we can apply CSS to our HTML?
The are **Two ways** of applying CSS to an HTML element.

The first method is to create an external CSS file using the **.CSS** extenssion and linking that to your HTML file.

TRhe second method is by using the **<style>** tag on your HTML file and writing all the CSS code inside that tag.

However, it is way better to use the first method.

## Why should we avoid using inline styles?
We should avoid using inline styles because it degrades performance as the page size increases.

## Review the block of code below and answer the following questions:

```
 h2 {
     color: black;
     padding: 5px;
   }
```

## What is representing the selector?

In this case the **h2** represents the selector.
The selector is the **HTML code** that we want to style.

## Which components are the CSS declarations?
The declaration is the **property** + the **value**.

In this case, **color** is the **property** and **black** is the value and togethr they form a CSS declaration.

## Which components are considered properties?

1. Color
2. Font
3. Box Properties
4. Positioning
5. Annimation



# Learn Javascript

## What data type is a sequence of text enclosed in single quote marks?
A **string** data type.

## List 4 types of JavaScript operators.
1. A ddition operator +
2. Assingment Operator =
3. Addition Assingment Operator +=
4. Logical Operator &&, ||, or !


## Describe a real world Problem you could solve with a Function.
Let´s say that we are collecting payments from customers. We can write a program that will notify us with the message **Payment Received** everytime a customer submits a payment.

However, this is a very repetitive task.

Therefore, we can insert our program inside a function. That way, the function will be called and the code will be executed everytime our company receives a payment from a customer.,


## An if statement checks a __ and if it evaluates to ___, then the code block will execute.
If a statement checks a TRUE statement and evaluates to TRUE, the code block will be executed.

## What is the use of an else if?
If statements are executed only if a condition is met.

In the example below, the phrase **Awsome dessert** will only be displayed ONLY if the dessert is tasty. If our dessert is not tasty, the message will not be displayed.

**For Example:**
```

cake = tasty;

if (cake == tasty){
  console.log("Awsome dessert")
}
```

## List 3 different types of comparison operators.

1. !== NOT EQUALS Operator
2. > Greater than Operator
3. < Less than Operator
4. >= Greater than or equals to Operator


## What is the difference between the logical operator && and ||?

&& is the **AND** operator and || is the **OR** operator.

&& will execute multiple conditions. On the other hand, || will execute one OR the other one.