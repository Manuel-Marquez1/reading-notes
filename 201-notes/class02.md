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