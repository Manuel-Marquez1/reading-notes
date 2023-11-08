# Table of Contents

1. [CODE-102 Notes](#CODE-102)
2. [CODE-201 Notes](#201-notes)


## CODE-102 




# My Reading Journal

Reading Notes October 4th.

# Introduction

Hey there!

My name is ManueL...
I live in Mexico City with my dog Rex. 
I love learning from Udemy courses (I have over 60 of them) 😩

In 2020, I attended college in Seattle as an international student and heard about the world of coding bootcamps.
As I grew in my career, it became obvious that I was going to need more technical skills.

In 2021, I moved back to my home country, changed my major to data science, and tried to gain as many technical skills as I could.
Nowadays, I'm an executive at a couple of nonprofits and work as a consultant.

My dream is to create the very first nonprofit coding school in Mexico and serve the people of my country by providing free CS education.

Here is a list of my favorite sandwiches...

+ The Philly
+ The cucumber sandwich with cream cheese (originally from the UK)
+ The BLT





# Read 06: Reflection and Discussion

## What is control flow?

Control flow is the order that the computer follows in order to execute a statement in a script.

The computer executes the code from top to bottom. Unless something changes the structure - loops and conditionals may affect control flow.

# What is a Javascript function?

A function is a set of instructions that perform a task.
Functions take and input and return an output, but there needs to be a relationship between  the input and the output.

Functions were created with the purpose of making our code re-usable.

## Example of a function

function divide_by_one (number) {
    return number / 1;
}

## We can also write a function using the following method

const divide = function (number){
    return number / 1;
};

## What does it mean to **invoke** or **call** a function?
Invoking a function means. Executing the function as soon as it is defined.

**For example**

(favNumber = function (num = 3){
    console.log("Your favorite number is" + num);
}

favNumber(5) <-- I am invoking my function again and passing a new argument

## What are the parenthesis for when you define the function?

The parenthesis are used to type our **parameters** or default values that we want our function to pass / have.

The parameter(s) inside the parenthesis allows us to pass data. 
For example: Any input that the user wants us to accept. 

**For example** The password to the user´s Netflix account.


# Read 08

## What is an expression in javascript?
An expression is a mix of operators, variables, values, etc.
However, they all evaluate to a single value.

**For example:**

 + > 17 + 9
 + > "Hello there!"
 + > hello.length

# Why would we use a loop in our code?

We use loops in order to perform actions over and over and over again.
Loops does this by **iterating** - which means that the loop will check each and every condition and it will stop until the condition becomes **False**.


# When does a for loop stop executing?

For loops understand booleans.
This means, that if a condition is **True** the for loop will continue working.
However, if at some point, the condition returns **False** the for loop will stop.

The **break** statement will also stop a loop from continuing to execute.


# How many times will a while loop execute?

A while loop will continue working as long as / **while** a condition is **True**.
However, once a condition returns **False** or encounters a **break** statement - the loop will stop working at that point.










  
  
