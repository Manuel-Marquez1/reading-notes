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



# Read 06 Reflection & Discussion

## What are variable in Javascript?

Variables are a container of data.
Many times when working with data, we need to find ways to manipulate big chunck of data.

Variables allow us to **store** our data

For example:

> var x = 5345.00000;

It would be very tideous to have to type 5345.00000 everytime I need to use it.

However, the variable **x** already stored the same value.

That way, I can just type...

> console.log(x)

Rather than having to code...

console.log(5345.00000)

# What does it mean to **declare** a variable?

In Javascript, declaring a variable is the same as **creating** a variable.
Once the variable has been created, we give it meaning by assigning a bariable.

**Here are 3 ways for declaring a variable**

const price = 45;
let price = 45;
var price = 45;

# What is an assingment operator, and what does it do?

Assingment operators assign values to variables.

let person = "Manuel";

In this case, the equals sign is the **assingment operator**. Because, it is **assigning** a value of Manuel to the variable person.

Now, if i console.log(person)

The output will be whatever was **assigned**. In thi case, it was the string value of Manuel.

# What is information received from the user called?

Information received from the user is called **input**.

Some people, also call it  **prompt**.

Let´s say that you want to get some money from your local ATM.

Most ATM machines are programmed with C/C++ code. However, let´s say that we want the ATM to ask the following questions...

**Insert your NIP**
**How much money you want to withdraw?**

The user goes ahead and will **input** the nip and the desired amount.
We call that information - user input.

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










  
  
