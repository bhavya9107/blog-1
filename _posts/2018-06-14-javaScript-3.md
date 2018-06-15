---
layout: post
title: JFS - First Steps with JavaScript 1
feature-img: "assets/img/javaScript.jpg"
thumbnail: "assets/img/javaScript.jpg"
tags: [blog, JavaScript, Programming, Fire Start, JFS, Prepare, Backpack]
---

Welcome again!! 🙌 <br>
Today you would write your first line of code in JavaScript and learn many more new exciting concepts and would be able to write some awesome 🤟 programs on very first day. As we have started journey, I would like to mention some important points about the Series:
- This series would give you strong fundamentals of programming which will help you start any difficult concept with ease in short **Makes your Basics right**
- If you are here to learn frameworks like **Angular** , **React** , etc. I'm afraid to say this course is not for you guys, But I would still recommend it as it deals with above point and will help you started quickly.

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
Wasn't that easy ?, But were to run it and where to right, let's findout now!!<br>
#### Creating javascript file
Now we would be creating a JavaScript file so that we can see our printing on action
- Create a folder (name it JFS or anything)
- Open folder on VS Code
    - if on windows, you can also right click on folder and select *Open with VS code* option
- Create a new file and name it ***index.html*** and insert following code
<div class="lang">HTML</div>
```html
    <html>
        <head>
            <title> JFS playground </title>
        </head>
        <body>
        <script src="learn.js"></script>
        </body>
    </html>
```
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
```javascript
    var variableName = value;

    /* Example of usage */
    var num = 1;
```
While `Arrays` are ***collection of variables*** under a single entity. Each variable in an array is accessable using it's **index** which start with zero. For example,

<div class="lang">JavaScript</div>
```javascript
    var arrayName = [val_1,val_2,val_3,.......,val_n];

    /* For Example */
    var nums = [1,2,3,4,5];
    
``` 
where val_1 is value of first variable in array, val_2 is of second variable till val_n.
> #### Index
  ---
  Index is the address of an individual variable in an array. They are zero indexed in JavaScript which means index of first variable in array is zero.<br>
  Now to access *2* in above declared array `nums` we would use index **1** as indexing starts from zero so we sould write `nums[1]` to get *2* from nums


Values of variables can be changed and not fix. To change the value use just use `=` operator, like you do in maths:
<div class="lang">JavaScript</div>
```javascript
    num = 2;
    // to change 3 in nums to 4 
    nums[2] = 4;
```
There is also another cool thing ( and sometimes irritating ) that is **type of a variable is not fixed in JavaScript**. So if you have assigned value ***2*** to a variable at some point of time it can be changed to ***"Hi"***.<br>
If you want type of a variable to be fixed there is a cool language **TypeScript** made by Microsoft to fix some flaws of JavaScript, discussion of TypeScript is out of the scope of this series but I would surely by writing abot it after this short series to give you a fire start in JavaScript.

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
`Arrays` have many utility functions which we would be disscussing in section 3.1 and 8.1 <br>
Hurray!! We sail through this section. Now you know how to declare a variable access it and update it's value. So know we learn about another fundamental block of programming that is `Conditional statements`.
`To be continued` while ask doubts, if you have any.