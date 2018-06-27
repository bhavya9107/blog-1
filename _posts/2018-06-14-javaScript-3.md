---
layout: post
title: JFS - First Steps with JavaScript 1
feature-img: "assets/img/javaScript.jpg"
thumbnail: "assets/img/javaScript.jpg"
tags: [blog, JavaScript, Programming, Fire Start, JFS, Prepare, Backpack]
---

Welcome again!! 🙌 <br>
As of now, you just have important information about JavaScript and have your environment set up complete, today we will get started with programming. You will learn how to print in JavaScript, know about variables and arrays and going to write conditional statements. So, Let's get started!!
First of all these are some important points about this series.
- This series would give you strong fundamentals of programming which will help you start any difficult concept with ease in short **Makes your Basics right**
- If you are here to learn frameworks like **Angular** , **React** , etc. I'm afraid to say that this course is not for you guys, But I would still recommend this course as it deals with above point and will help you started quickly.

It is first of the three Sub-series in JavaScript Fire Start Series, named `First Steps with JavaScript`. It is focused on people with NO experience or very little experience in JavaScript and in general programming.

## Post Structure
2. **First steps with JavaScript 1** <br>
>   2.1 Print to Console <br>
>   2.2 Variables and Arrays <br>
>   2.3 Conditional Statements<br>

## *2.1* Print to Console
One should obviously know that how to see output of a program.
In JavaScript its very simple:

<div class="lang">JavaScript</div>
```javascript
    console.log("We are learning JavaScript");
```
Wasn't that easy ?, But were to run it and where to write, let's find out now!!<br>
#### Creating JavaScript file
Now we would be creating a JavaScript file so that we can see our printing on action
- Create a folder (name it JFS or anything)
- Open folder on VS Code
    - if on windows, you can also right click on folder and select *Open with VS code* option
- Create a new file and name it ***index.html*** and insert following code
<div class="lang">HTML</div>
````html
<html>
    <head>
        <title> JFS playground </title>
    </head>
    <body>
    <script src="learn.js"></script>
    </body>
</html>
````
- Create another file and name it ***learn.js*** and write the code to print **"We are learning JavaScript"**
<div class="lang">JavaScript</div>

```javascript
    console.log("We are learning JavaScript");
```
- Now run the file ***index.html*** using any browser
- Open developer tools
    - In most of the browsers it can be viewed using `Ctrl+Shift+I` shortcut
- See your output under console section

Now you can write on your browser 👌!!<br>
We just reached end of this section, Now we would be discussing about ``Variables and Arrays`` !!

## *2.2* Variables and Arrays
`Variables` are individual entities whose value isn't fixed. Its value can be changed at any point of time. They are assigned in using following syntax:
<div class="lang">JavaScript</div>

````javascript
    var variableName = value;

    /* Example of usage */
    var num = 1;
````
While `Arrays` are ***collection of variables*** under a single entity. Each variable in an array is accessible using it's **index** which start with zero. For example,

<div class="lang">JavaScript</div>

````javascript
    var arrayName = [val_1,val_2,val_3,.......,val_n];

    /* For Example */
    var nums = [1,2,3,4,5];
    
```` 
where val_1 is value of first variable in array, val_2 is of second variable till val_n.
> #### Index
  ---
  Index is the address of an individual variable in an array. They are zero indexed in JavaScript which means index of first variable in array is zero.<br>
  Now to access *2* in above declared array `nums` we would use index **1** as indexing starts from zero so we should write `nums[1]` to get *2* from nums


Values of variables can be changed and not fix. To change the value use just use `=` operator, like you do in maths:
<div class="lang">JavaScript</div>
```javascript
    num = 2;
    // to change 3 in nums to 4 
    nums[2] = 4;
```
There is also another cool thing ( and sometimes irritating ) that is **type of a variable is not fixed in JavaScript**. So if you have assigned value ***2*** to a variable at some point of time it can be changed to ***"Hi"***.<br>
If you want type of a variable to be fixed there is a cool language **TypeScript** made by Microsoft to fix some flaws of JavaScript, discussion of TypeScript is out of the scope of this series but I would surely by writing about it after this short series to give you a fire start in JavaScript.

#### Challenges
##### Q> Write a code to print value a variable which has value ***23***
Solution:
<div class="lang">JavaScript</div>
```javascript
    var a = 23;
    console.log(a);
```
---
##### Q> Write a code to print value a variable which has value as sum of 2 and 3
Solution:
<div class="lang">JavaScript</div>
```javascript
    var a = 2 + 3;
    console.log(a);
```
---
##### Q> Write a code to print value 4 from array nums = [1,2,3,4,5]
Solution:
<div class="lang">JavaScript</div>
```javascript
    var nums = [1,2,3,4,5];
    console.log(nums[3]);
```
---
`Arrays` have many utility functions which we would be discussing in section 3.1 and 8.1 <br>
Hurray!! We sail through this section. Now you know how to declare a variable access it and update it's value. So know we learn about another fundamental block of programming that is `Conditional statements`.

## *2.3* Conditional Statements
Suppose you go to a smartphone shop there you liked two smartphones:
1. `IPhone X`
2. `Redmi note 5`<br>
Now you are confused and started thinking<br>
<br>
***If** I Buy IPhone X*: Brand name and have many features <br>
***else** If I buy Redmi note 5*: Cheap price and value for money<br>

In programming your thought process resembles a fundamental block named `Conditional Statements`.

>**Conditional Statements** are used if we have to impose restrictions on certain lines of code to meet some conditions before they can be executed.

In JavaScript Conditional Statements can be implemented using :
1. `If else` statements
2. `switch` statements
3. `ternary` operator

#### If else statements
If else statements are most logical to new programmers. It is very simple and easy to implement:
<div class="lang">JavaScript</div>

````javascript
/* Syntax */
if(condition 1){
    // Statements to be executed if condition 1 is true
    .
    .
}
else if(condition 2){
    // Statements to be executed if condition 2 is true
}
.
.
else{
    // Statements to be executed if all conditions are false
}



/* Example */
if(bankBalance>200000){// Currency unit Rupees
    console.log('Buy IPhone X');
}
else{
    console.log('Buy Redmi note 5');
}


````
Easy!!

#### switch statements
switch statements are used if conditions doesn't involve comparisons and are dependent on a single variable.

<div class="lang">JavaScript</div>

````javascript
/* Syntax */
switch(variable){
    case val_1:
        // Statements to be executed if variable 
        // has value equal to val_1
        break;
    case val_2:
        // Statements to be executed if variable 
        // has value equal to val_2
        break;
    .
    .
    default:
        // Statements to be executed if variable
        // has non of the above mentioned values
}

/* Example */
switch(smartPhone){
    case 'IPhone X':
        console.log('Brand name and have many features');
        break;
    case 'Redmi note 5':
        console.log('Cheap price and value for money');
        break;
    default:
        console.log('Unknown Smartphone');
}


````
Simple !!

## ternary operator
if one have to assign value to a variable as per certain condition than we use ternary operator (also known as conditional operator)

<div class="lang">JavaScript</div>

````javascript
/* Syntax */
variable = condition ? val_1 : val_2;
// val_1 will be assigned to variable if
// condition is true else val_2 will be assigned

/* Example */
var smartPhone = bankBalance>200000 ? 'IPhone' : 'Redmi Note 5';

````
Awesome !!
