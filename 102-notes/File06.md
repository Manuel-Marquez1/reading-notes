# Class 06: Javascript

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
