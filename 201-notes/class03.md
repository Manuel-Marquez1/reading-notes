# Class 03: Lists, The Box Model, and Loops

# Notes from Class 03
You can turn the career assingments until the last day of class. Just make sure that you submit them at the end.

In class we also had a code review.

We also reviewed the "use strict" line of code.

As well as concepts such as **alert()** and use of **string template literal**.

**Functions:** A way to execute statements.

**Objects** A function is an object. Pretty much everything in Javascript is an object.

**.loLowerCase()** this method stores the data in lowercase even if the informattion provided was in uppercase.

We learned about **control floww**. However, we will later learn about how to respond to events and the usage of the DOM.

We learned about how to code **increments / score keepers**.

At the beginning of the class, we also have a good example on how to clone Github repos.

# Course Outline

+ Control Flow and Box Model
+ Code demo
+ Arrays and Loops
+ The box model
+ Lab prep

# Arrays

They are another **Datatype & Data Structure**.
Their data type is an **Object**.
They are a collection / list of elements.
You can store numbers, strings, lists, etc all in the same array.
You do not have to determine the size of your array upon creation.
They are indexed based. Every element has a position.

```javascript
//                0         1        2      3
let myArray = ["Hello", "goodbye", "hi", "bye"];
```

# Array Methods

You can also chain up orattached methods on an array.

## Method Number 1 .push()
It adds an elements to the end of the array.

## Method Number 1 .pop()
This method will remove the last element of the array.

# Array Properties
A property is what makes an array a thing.

.length  <-- This will tell us how many elements are in an array / the size of it.

# EXERCISE

```javascript
`use strict`;

let nums = [3,5,7,9,11];

//When printing the contents of an array use the following console
// console.table(nums); <-- Helpful when you need to see the index
//Remember that an array is like a matrix


let mixed = [`hello`, true, [1,2,3]];


```

# Referencing elements inside an array with Bracket notation


```javascript

`use strict`;

let mixed = [`hello`, true, [1,2,3]];

// Reference OR grab the boolean value

let myBoolValue = mixed[1]  // Our input is 1 because that is the index of that boolean
console.log(myBoolValue)  //true  <-- Boom!!! we just referenced our boolean

//We are NOT removing anything we re just creating a copy



```

Note to self: Practice grabbing elements from nested arrays.

## We can also assign or add elements on the array

```javascript

`use strict`;

let students = [`Jesse`, `Gerald`, `Jennifer`];

// Let´s assign values based on Index

students[3] = `John`;

console.log(students)

//Output: `Jesse`, `Gerald`, `Jennifer`, `John,

```

# Typical use case for adding to an Array

Do the **Push Method**.

Remember **Push** will add to the end of the array.

```javascript

`use strict`;

let students = [`Jesse`, `Gerald`, `Jennifer`];

students.push("Cooper");
students.push("Jimmy");
students.push("Manuel");

```

# The length property
It tells you the size of the array.

console.log(students.length); // It will tell us the size of the array
This method will also count empty spots

## Example of when an array is used.

If a user of a to-do list wants to add new items.
The data can be stored in an array and you can use the push method to add items at the very end of the list.

# Removing from an Array .pop() Method
We will use the **.pop() method** to remove the last element from the array.

Recomendation: store the .pop() method on a variable so you can use it later.


```javascript

`use strict`;

let delete = students.pop();
console.log(delete);

```

# Loops
loops xecute code over and over again until we tell them to stop.

We will talk about 2 loops - for loops and while loops.


### For loops

- We use it to execute code a certain number of times.
- It is also great for looping over an array. because arrays have sizes and for that we use the length property.

```javascript


// Anatomy of a for loop

for(starting value; condition; increment / decrement){
    //code block will run only if the condition is true
    // The code will stop running once the condition is no longer true
}
```

### While loops

- Executes code until the condition that is given is no longer true
- Beware of infinite loops

```javascript


// Anatomy of a while loop

while(condition){
    //code will run until the condition is no longer true
}
```


### For loop example

```javascript

`use strict`;

let nums = [1,2,3,4,5];

for(let i= 0; i < nums.length; i++){
  console.log(nums[i])

}

// i=0 is the index where the loop will start
// i reffers to the index value / element
// i < nums.length as long as the array nums is less than the length of the array nums - the condition will be set.
// i++ will move to the next index / It adds one to i / we increment it by 1.
```


# Read Class 03

# Learn HTML

1. When should you use unordered lists in your HTML document?

You should use **unordered lists** when the order does not matter. For example, when we are mentioning random information like names of differents bands, colors, dog breeds, etc.

2. How do you change the bullet style of unordered list items?

Whwnever we are working with unordered list itesm, it is very likely that the list items will be nested on the **ul** tag.

The code could look something like this...

```html
<ul>
  <li>Banana</li>
  <li>Apple</li>
</ul>
```
Notice how on the code block above, the list items are wrapped by the **ul** tag.

However, we will now create the same list but with an **ordered style**. We will achieve this by changing the **ul** tag into an ordered list tag **ol**.

```html
<ol>
  <li>Banana</li>
  <li>Apple</li>
</ol>
```
The **ol** tag will give us a numbered / ordered list now instead of giving us random bullet points.


3. When should you use an ordered list vs an unorder list in your HTML document?

We will use an **ordered list** whenever the order of a sequence is important.
For example: We will use an ordered list whenever we are adding recepies to our website.
Or instructions / step-by-step manuals of products.

On the other hand, we will use an **unordered list** whenever we dont have to worry about the order of something.

For example, whenever you are dealing with nominal data like the number of players in a soccer field, a random list of lottery tickets , or even a random list of the appartments that are available for rent in a building.



4. Describe two ways you can change the numbers on list items provided by an ordered list?

If you want of doing this is by using the CSS property
> list-style-type

The following code will change the ordered list into an unordered list by converting the numbers into bullet points.

```CSS
ol {
  list-style-type: disc;
}

```

The second way is by changing the **ol** HTML tag into a **ul** HTML tag.


# Learn CSS

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

In football, the players spend most of the time controlling the inside of the court.

However, the coach of the team, spends most of the time on the outside of the court.

Every NFL court, contains a logo in the middle of the court.

The padding is what sorrounds that logo and the players only control the center or the sorroundings of the logo.

On the other hand, the margin is the space where the coach of the team is located. He has control of that space between the court and the seats where the fans are located.

2. List and describe the four parts of an HTML elements box as referred to by the box model.

+  **Content:** This is the part that contains text, images, and other message or data that we want to display.

+  **Padding:** It is the space between the content and the border of the box. It is an invicible space but it adds space to the content of the box.

+  **Border:**  It is a visible line that outlines the element. It is the visible boundarie of the element.

+  **Margin:**  It is the lement that controls the spacing outside of each element. However, it does not control the element.

# Learn Javascript

1. What data types can you store inside of an Array?

Any type of data can be stored in an array. We cann store Numbers, strings, even other arrays (nested arrays).

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```javascript

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

 ```
 Yes, this still a valid array. This array it is stored in a variable called people which is also an object.

 We can access those values using bracket notation. It is important to notice that we can access those elements because each **nested array** has an **index value**.

3. List five shorthand operators for assignment in javascript and describe what they do.

- **Addition Operator (+=):** Adds the value of a variable and assigns the result back to the vaeriable.

- **Substraction Operator (-=):** Subtracts the value of the variable and assigns the result back to the variable.

- **Multiplication Assingment Operator (-=):** Multiplies the value of the variable and assigns the result back to the variable.

- **Divition Assingment Operator (-=):** Divides the value of the variable and assigns the result back to the variable.

- **Exponentiation Assingment Operator (-=):** Takes the value of a variable and raises the value to the chosen exponent

4. Read the code below and evaluate the last expression and explain what the result would be and why.


```javascript
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
```
### Answer

The result is **10dog** because **a** has a positive value of 10.
The boolean **false** has a numeric value of 0.
**'dog'** is inserted besides 10 because javascript is contantinating the values.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

Let´s say that you are on Facebook (Meta) or Reddit and you want to like a picture or a post.
However, if you have not created an account with these apps before, a message will pop up asking you to register or sign-in.

So instead of being able to like a picture or a post - the app will instead encourage you to sign-in or create an account.


### Example 1

```javascript
realUserAccount = True
notUser = False

if(realUserAccount == True){
  console.log("You are a real user! Please explore our platform");
  else{
    alert("please sing-in");
  }

}

```



6. Give an example of when a Loop is useful in JavaScript.

Using the previous example, let´s say that you are not a user of Reddit and you tried to like a picture but Reddit sends you an alert / pop-up asking you so sign up.

Once you create an account, we want to display a message that says "Welcome to Reddit". However, we also want the icons of many baloons to be displayed.

The code could look something like this...

### Example 2

```javascript
realUserAccount = 1;
welcome_Message = ["Welcome!!! 🎈"];

if(realUserAccount){
  console.log("You are a real user! Please explore our platform");
  else{
    for(let i = 0; i < 2000; i++){    // Welcome message is displayed 2000 times
      console.log(welcome_Message) 
    }
  }

}

```

# Things I want to know more about

1. How to maniputale arrays with bracket notation.
2. How to be more efficient when writing for loops and coditional statements.
3. Learn more array methods