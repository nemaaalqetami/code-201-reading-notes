## Chapter 2 :


When we creating a web page, and add tags.
This tags provide extera meaning and all browswrs to show user the structure for the page .

we will talk about :

 - Structure markup : the elements that you can use to describe both headings and pragraphs.
 - Semantic markup : which provides extra information , such as where emphasis is placed in a sentence .





## Structure markup :








 ### Heading :







 HTML has six `level` of headings 
 it's use for heading and subheadings
 `h1` is used for heading
 `h3` is used for subheadings







  ### pragraphs :
   browser will show each pragraphs on a new line with some space between it .






   `<p> yout content </p>` this tag used for pragraphs.

   for designing the text or just a word we use `bold & italic tags`
   this Example :


   `<b>your content</b>` this tag makes your text bold
   `<i>your conten</i>` this tag makes your text italic


if you want to begin a new line you should use `<br>` tag 
if you want to makes divider between the lines you should use `<hr>` tag 



## Semantic markup :


- The `<article>` element specifies independent, self-contained content.
- The `<aside>` element defines some content aside from the content it is placed in (like a sidebar).
- The  `<details>` tag Defines additional details that the user can view or hide
- The `<header>` element represents a container for introductory content or a set of navigational links.
- The `<footer>` element defines a footer for a document or section.
- The `<nav>` element defines a set of navigation links.
- The  `<figure>` tag specifies self-contained content, like illustrations, diagrams, photos, code listings
- The `<figcaption>` tag defines a caption for a figure element. The figcaption element can be placed as the first or as the last child of a figure element.
- The `<main>` tag Specifies the main content of a document
-  The `<mark>` tag Defines marked/highlighted text
- The `<section>` tag Defines a section in a document
- The `<summary>` tag Defines a visible heading for a details element
- The  `<time>` tag Defines a date/time



## Chapter 10 :



###  CSS Introduction




####  What is CSS?
 
 + CSS stands for Cascading Style Sheets
 + CSS describes how HTML elements are to be displayed on screen
 + CSS saves a lot of work. It can control the layout of multiple web pages all at once
 + External stylesheets are stored in CSS files
 
 


you can use the css to style your `HTML` elements in three approach :
1. inline styling 
2. internal styling 
3. external styling

`and the most common is external styling because it reusable the developer can use it for more one html page`




 A CSS rule contains two parts

 Selector :
 + you can use element html selector 
 EX 
 you have a paragraph and you want to styling 
 p {
 your styling
 or 
 declaration
 }
 this method can styling every  paragraph in your page 
 + id selector it has be unique for one element in your page 
 + class selector you can use it for multiple element in your page 
 
 Declaration : what you writing inside the selector to element be styled
 
 
 also css  consists a set of CSS properties.The CSS properties specifies what to style of the targeted HTML elements

Ex 
 img src="the path of the image "

tag image has specific property we couldn't use it with other tags and use it for the path of the image,and can specify the size and width of the image
it has It has a large number of properties, it also uses colors and their values
  EX:
  
  color : value (what color you wnat)
  You can write in  hexadecimal

You should know that Css has many rules that you will surely know by practice.



# JavaSecript :



### Chapter 2 :



####  Basic JavaSecript : 

A script is a series of instructions that a computer can follow one by one .


`What is a variables` : Hold the data value and it can be changed any time .

How to declare them :

`var x = 1` this the syntx to declare variables and assign them a value .

`What is a Data Type` : there are 3 data type in js

Number , String , boolean 


- using variables to declare a number 

`var price = 3;`

- using variables to declare a string 

`var username = 'omar';`

- using variables to declare a boolean ,the boolean data type have just to values `true ot false `

`var result = false ;`
 


## Chapter 4 : 

Decision Making :

There are often several placed in a script where decision are made that determine which lines of code should be run next.


conditional Statments :

a conditional Statments says what to do in a given situation.


Comparison operators Evaluating conditions :


And : this operator tests more than one condition.

OR :this operator tests at least one condition.

Equals == : this operator compares two values(numbers , strings , booleans ) to see if they are the same

< : less than ,this operator checks if the number on the left is less than the number on the right



 `if` Statements :
 the if statements evaluates or checks a condition ,if the condition evaluates to `true` any statements in the subsequent code block are executed.

  `if ... else` Statements :
  
  the  if ... else checks a condition. if it resolves to true the first code block is executed,if the condition resolves to false the second code block is run instead.


  `Switch` Statements :
   a switch Statements start with a variable called the switch value ,each case indicates a possible value for this variable and the code that should run if the variable matches that value .
