
## Html
##### Introduction
###### How Websites Are Created :
Small websites are often written just using HTML and CSS.Larger websites those that are updated regularly and use a content management system (CMS), blogging tools, or
e-commerce software — often make use of more complex technologies on the web server,but these technologies are actually used to produce HTML and CSS that is then sent to the browse


How the Web Works ?

When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.

Structure:
HTML Uses Elements to Describe the Structure of Pages ,There are several different elements. Each element has an opening tag and a closing tag.Tags act like containers. They tell you about the information that lies between their opening and closing tags.
Ex : 

`<p> this is opening tag`
`</p> this is closing tag`
`<img/> this is called it self closing tag`
Attributes : is tell us more about elements, attibutes provide information about the content of an element ,they appear on the opening tag ,and are made up of two parts 
name and value  separated by an equals sign.


Ex:

`<a src="">your content </a> attributes `src` ,here we can  provide the url about the link,
let me show you the html structure
firt we should begin 
<!DOCTYPE html > that tag tell the browser what version of html we use it 
<html>
<head>
</head>
<body>
</body>
</html>
insid head tag we can write the name of our website using tittle tag
insid body tag we write all elements of html.`


Extra Markup :



 ### DOCTYPE 
`stands for Document Type Declaration`
Tell the browser what version of html we use , and must be begin with it
for html5 ,we use it `!DOCTYPE html` but it's not considered an element or html tag and every version of html has own DOCTYPE




### Comments in HTML : 
 developers use comment to leave notes to understand each other
 also, the developer comment the element of html because doesn't need it  but can use it again any time

`<!-- comments parts  -->`



### ID Attribute :

id attribute must Unique for styling just `one element in html` and should be starting `# ` sign and the name of id then call it in youe element ` <p id="the name of class">` like that .
 
 
 

 ### CLASS Attribute :
 class attribute it used for styling multiple elements  and should be starting `. ` sign and the name of class ,then call it in youe element ` <p class ="the name of class">`


  `<div>` tag is used for defining a section of your page and can   
       contain another div inside it

  `<span>` tag is used for to styling or organizing a part of content 

  `<iframes>` tag is organizing your content to look like box and
       you can scrolling it
    `<meta>` tag is not displayed to website visitor but is provided for 
    use by browsers and web , also is used to `add machine-readable information to an HTML pages`
      
      
`<character escape>` is a way pf representing a character using only   

 ASCII characters 




 
 
 # HTML5 Layout :

In this chapter we gonna tolk about `HTML SEMANTIC ELEMENTS`

 What are Semantic elements ?
 Semantic elements = elements with a meaning.

 this is exaple for Semantic elements.

 

* The `<article>` element specifies independent, self-contained content.
* The `<aside>` element defines some content aside from the content it is placed in (like a sidebar).
 * `<details>` tag Defines additional details that the user can view or hide
* The `<header>` element represents a container for introductory content or a set of navigational links.
* The `<footer>` element defines a footer for a document or section.
* The `<nav>` element defines a set of navigation links.
* The `<figure>` tag specifies self-contained content, like illustrations, diagrams, photos, code listings
* The `<figcaption>` tag defines a caption for a figure element. The figcaption element can be placed as the first or as the last child of a figure element.
* The `<main>` tag Specifies the main content of a document
* The `<mark>` tag Defines marked/highlighted text
 * `<section>` tag 	Defines a section in a document
* `<summary>` tag Defines a visible heading for a details element
* `<time>` tag Defines a date/time




 # Process & Design :
 
 `SITE MAP`




###  What is a sitemap ?



A sitemap is a file provides  a description about the pages
and other files on your site 



### you need a sitemap : 



* if your site is very larg   
* if your page are not linked to each other you can list them in a       sitemap
* if your pages has large number of media content 





 ### you not need a sitemap :
 
 
 
 * if your site is small
 * if you dont have a lot of media in your site


###  What is a wireframe ?




 
Wireframing is a way to design a website but Manually before usit the code edittor it gets your client thinking about what their needs and functional requirement will be more clarity and it Giveing  to the developer more clear and initial picture how the user interface would be

when you desiging a wireframe tring to avoid 
 
 * Too much detail
 * you don't need to Creating wireframes for every single page

 Finally, make sure that your website has a simple user interface, easy to use and this is what the user needs .




## javascript 





#### Introduction :

we explains how JavaScript can be used,in browsers to make websites more interactive, interesting, and user-friendly. Learning to program with JavaScript involves:
- basic programming concepts
- Learning the language itself
- Becoming familiar with how it is applied 

how javascript makes web pages more interactive:

1- ACCESS CONTENT

2- MODIFY CONTENT

3- PROGRAM RULES

4- REACT TO EVENTS

EXAMPLES OF JAVASCRIPT IN THE BROWSER
1- SLIDESHOWS

2- FORMS

3- RELOAD PART OF PAGE

4- FILTERING DATA




#### Secript :




What is ascript and how do i create one ?

A SCRIPT IS A SERIES OF INSTRUCTIONS

A script is a series of instructions that a computer can follow to achieve a goal.

You could compare scripts to any of the following

1- RECIPES

2- HANDBOOKS

3- MANUALS

Writing  A Script :

To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. 
Designing a Secript Tasks :
you can work out the individual tasks needed to achieve it.

EVENTS :
WHAT IS AN EVENT? 

events are "things" that happen to HTML elements.When JavaScript is used in HTML pages, JavaScript can `react` on these events.

WHAT DOES AN EVENT DO?

Programmers choose which events they respond to.When a specific event happens, that event can be used to trigger a specific section of the code.Scripts often use different events to trigger different types of functionality .
How a Browser sees a Web Page ?
1-  Receive a Page as Html Code
2- creating a model of the page and store it in memory.
3- use a rendering engine to show the page on screen.

How Html ,Css and JavaScript work Together?

HTML, CSS and JavaScript work together to form the front-end design of a website by applying information that affects content, style and interactivity of a site.


How to use `Object and Methods` ?
this ome line of javaScript shows how to use object and methods programming refer to this as calling a method of an oblect.
Ex :
document.write("")
the document object represents the entire web page.
the wrire() method or`Function` of the document object allows new content to be weitten into the page.
and we can add html element in this method














