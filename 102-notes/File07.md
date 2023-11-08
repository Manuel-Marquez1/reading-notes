# Class 07: Programming with Javascript

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
