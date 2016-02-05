# JavaScript Basics
## Conditional Statements
###### Remixed from the Flatiron School: CSSI Curriculum
---

# What You Will Learn:
+ What conditional statements are
+ Why we use them
+ JS conditional statement syntax
+ if/else statements
+ if/else if statements
+ Comparison operators
+ Introduction to Logical Operators

# Conditional Statements
Now that we are getting the hang of manipulating our variables, let’s experiment with conditional statements. A conditional statement is a set of commands that executes if a specified condition is true (remember our data type boolean, with a value of true or false?)

```
if (condition){
  statement_1
}
else {
  statement_2
}
```

Let’s make an if/else statement for our var collegeGpa = 4.0

```
if (collegeGpa == 4.0) {
  alert("Doing mighty fine!");
} else {
  alert("Let's hit the books!");
}
```

Notice the syntax for our conditional statement in JS:
+ conditions are in parenthesis,
+ blocks are in curly brackets {}
+ expressions end with ';' semicolons.

Notice also our use of indentation. JavaScript doesn't need indentation to work, but it makes code way easier to read. When we move to python, the wrong whitespace will break our program, so it’s good to get used to indenting now. Plus, then you can read what's going on!

We can make our if/else statement more complex and more specific by adding an additional conditional statement with else if:

```
if (collegeGpa >= 4.0) {
    alert("Doing mighty fine!");
} else if (collegeGpa > 3.0) {
    alert("Not too shabby!");
} else {
    alert("Let's hit the books!");
}
```

You’ll notice we’ve been using some new operators in our conditional statements, like '==' and '>='. These are our comparison operators. Notice the difference between using a single = and the double '=='.

What is the difference? '=' assigns a value, '==' checks if two values are equal.

'==' is one of the **comparison** operators. They let you express conditions like equality and inequality. They evaluate to True or False, so they are really useful in conditional statements.

Here is a list of all of JS comparison operators and what they do

<img src="https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.5-conditional-statements/master/js-boolean-operator-table.png">

We can add even more complexity to our conditional statements with logical operators. These let us combine conditions. Is x greater than 4 AND less than 7?

Here is a list of all the Logical Operators and what they do:

<img src="https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.5-conditional-statements/master/js-logical-operators.png">

# Student Challenges

### Task 1  
**Skee-ball Rater**

![Skee-ball](http://robertkaplinsky.com/wp-content/uploads/2013/03/skeeball_cover.jpg)

Prompt the user for their Skee-ball score.

Create a conditional statement that uses `alert()` to show the rating of a Skee-ball player based on their score.

If you’re not up on your Skee-Ball scoring, a score <150, is pretty bad. A score of 150-250 is decent. A score of 250-350 is good. A score between 350-450 is great. A score above 450 is amazing!!!

Be creative with the messages you write!

### Task 2  
**Mini-Challenges**

1. Write a JavaScript program that accepts two integers and displays the larger one.
2. Write a JavaScript conditional statement to find the sign of product of three numbers. Display an alert box with the specified sign.
+ Sample numbers : 3, -7, 2
+ Output : The sign is - 

3. Write a JavaScript conditional statement to sort three numbers. Display an alert box to show the result. Go to the editor 
+ Sample numbers : 0, -1, 4
+ Output : 4, 0, -1 

4. Write a JavaScript conditional statement to find the largest of five numbers. Display an alert box to show the result. Go to the editor 
+ Sample numbers : -5, -2, -6, 0, -1
+ Output : 0 

5. Write your own mini-challenge!
