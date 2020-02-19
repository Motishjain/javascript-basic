# Variables & Loops

## Overview

In this topic, we will understand 'variables' which are the basic building blocks of any program, what data they can hold 
and how we can convert data from one type to another using type conversions.

We would also cover an interesting control flow in programming called 'Loops'. In simple terms - Eat. Sleep. Rave. Repeat is one kind of a loop :)
 In programming, this is a very important construct as almost every algorithm you would see will be using this.

## Learning Outcome

- What is a variable?
- Different types of data which can be assigned to a variable?
- How to convert data from one format to another?
- How to write loops?


## Introduction

*Variable*

As the name suggests, a variable is anything that can vary. It can hold data in different formats (which will be covered below) and it can be changed anytime. A variable can hold different types of data like Numbers(5,6,7), Strings("Hello World"), Boolean(true/false), etc.

In JavaScript, you can assign new data of a different type to the same variable. A variable holding a particular type of data can be converted to another type by typecasting. The below shared articles explain how typecasting works.

*Loops*

A loop is a block of code written to be executed repeatedly. There are three parts of a loop i.e. Assignment, Condition and Update statement.

for (i = 0; i < 5; i++) {
  //Block of code to be executed
}

The first statement "i=0" gets executed once which is the starting point of the loop. The second statement "i<5" is the condition for the loop to continue which evaluates everytime after the 3rd statement (Update) is executed. "i++" is the Update Statement which runs everytime after the block of code is executed.

The sequence looks something like below -
i = 0 (Runs only once)
// Execute the block of code
i++ // This updates i to 1
i < 5 // If this returns true, loop continues from the block of code


## What must you do?

-	Familiarize yourself with [different data types in JavaScript](https://www.geeksforgeeks.org/variables-datatypes-javascript/). 
-	Next step is to understand [how data is converted from one type to another](https://www.w3schools.com/js/js_type_conversion.asp)
- Once understanding variables and it's data types is clear, go through [this article](https://www.w3schools.com/js/js_loop_for.asp) to understand how loops work in JavaScript.


## Additional Resources
- Here is a [detailed and easy to understand](https://javascript.info/variables) article explaining JavaScript variables and how the data types work.
- [Different Type of Loops in JavaScript](https://www.edureka.co/blog/javascript-loops/) - In case you're interested to know about them
