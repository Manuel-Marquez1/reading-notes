# Class 01

For class 01, we created a basic web page using the javascript commands alert and prompt.
You can access the code by clicking the link below.

[Code of Lab-01](https://github.com/Manuel-Marquez1/reading-notes/blob/main/Lab-01.html)


# Class 01 Reading

# Getting Started

## Compose a short poem describing how HTTP sends data between computers

Our browser send a request to the server. The server returns to us all the HTML, CSS, and Javascript files that will form our website. The files are returned to us "The client" and are displayed as a website.

## Describe how HTML,CSS, and Js files are "parsed" in the browser.

The browser recognizes the **<link>** elements on every CSS file.
Once the browser has parsed the HTML file (initial file) with our CSS file - it sends a request to the server for any CSS files with a **<link>** element.

Last but no least, the browser does the same with Javascript files. The browser recognizes Js files due to the **< script >** element.

## How can you find images to add to a website?
A good place for finding images is **Google Images**.

However, something that we learned at CODE-102 is that if you are using an image - it is always better to give credit / mention where you got the image from.

We can use images that do not have any copyright too OR use the **license filter** on the Tools button of our browser.

## How do you create a String vs a Number in Javascript?

In order to create **numbers**, we can actually type any number (whole numbers, decimals, etc)

Numbers are more of a data type. However, Javascript will assign the same data type to any number. It does not matter if the number is a decimal or a whole number.

For example...

```
typeof 3.1416  //Returns a number
```

A second example

```
typeof 3  //Also returns a number
```

On the other hand, **strings** is data / characters wrapped in quotation marks and each value have an index. The index always starts at zero.

```
"This is a string" 
```
On a previous example...

```
let name = "Manuel";   //Manuel is information stored in a string. 
```

Strings are also important because they allow us to store any type of **characters** and easily have access to it.

## What is a variable and why they are important in Javascript?

Variables are containers that store data / information.

They are important because they allow us to store large amounts of data and access it, modify it, or tranform it

In order to create a **variable** on javascript you can use one of the following 3 keywords.

**var, const, OR let**

You select one of the three keywords, give a name to the variable and assign a value to it.

Last but not least, you add a semicolom at the end.

For example: I will create a variable known as **name** and I will store my own name on it.

```
let name = "Manuel";
```

# Introduction to HTML

## What is an HTML attribute?
Attributes provide additional information about HTML elements.

**href** is an attribute that allows us to link elements.

**src** is an attribute that specifies the path to a file.


## Describe the Anatomy of an HTML Element
The anatomy of an HTML element consist of mainly 2 things...
1. An opening Tag
2. A closing tags

**An opening tag** + **a closing tag** = **One element**

The content also goes inside the HTML element.
In other words, the content goes inside the opening and closing tag.

Something important to mention is: There are self-closing tags as well.

Those self-closing tags have an opening tag but DO NOT have a closing tag.

For example:
1. **<link>**
2. **<br>**
3. **<img>**
4. **<hr>**

## What is the difference between an <article> and <section> tags?


## What elements does a "typical" website include?


## How does metadata influence Search Engine Optimization?


## How is the <meta> HTML tag used when specifying metadata?


# Miscellaneous

## What is the first step to designing a website?

The first step to designing a website is **planning**.
During this phase, we ask questions like...

+ What is my website about?
+ What information will be presented about the subject?
+ What does my website look like?

Once this phase has been completed, we can move tothe next stage known as **sketching**.


## What is the most important question to answer when designing a website?


# Semantics

## Why should you use an **<h1>** element over a **<span>** element to display a top level heading?


## What are the benefits of using semantic tags in our HTML?


# What is Javascript?

Javascript is a programming language that adds interactivity to our website.

## Describe 2 things that require Javascript in the browser?


## How can you add Javascript to an HTML document?
In order to add a Javascript file to your HTML file, we can take the following steps...

1. Create a main.js file on your code editor.
2. Go back to to your HTML file and inside the <body> element - link the js file.
3. In order to link the js file we will use the script tag.

```
<script src="file_name.js"><script>
```
4. YOU ARE DONE!!!