#Web Development Course
#HTML(Hyper text Markup Language)

#Day1 Intro to HTML
Objectives:
HTML?
HTML Document Structure
Basic HTML tags(Parrgraph,Headings, Links,List)
Inline Elements


Basic HTML Tags: Tags enclosed within angle brackets<>
Tags Type
Paired Tags(Container Element): Opening and Closing tags
#<p> </p> et
Unpaired Tag(Empty, Self closing ):
#<br>

#Heading It has six level 
<h1> to </h1>

#Parrgraph : It used to created using <p>

#List :Html support 2 types of lists
1. Ordered List
It display with numbers

Ex Myroutine list
<ol>
<li> Prayer</li>
<li> Bf </li>
</ol>

2. Unordered List : It display items with bullets
Exp
<ul>
<li>Apple</li>
<li>Banana</li>
</ul>

Links: It allow users to navigate to another webpage.
<a href="URL Link"> Text of Link </a>

Inline Element:Occupy only the space needed by their content and don't start on new line

<span>: Genreic inline Container
<a>: Hyperlinks
<strong>: important (bold) text
<em>: Emphasized(italic) text
<i>:italic text
<b>: Bold text

#HTML: It is used to create and strucutre webpages.
It is not progrogramming language. markup langauge
It tells the browser what should we display on the page, how content is organized

#Basic HTML document Structure
<!Doctype html> #It tells the browser that this document uses HTML5
<html> ##Root element that contains entire the web page

<head># Contains information about the web page that is not directed display 
#Example : Title , CSS, Metadata

    <title>Bismillah </title> # Display the webpage title on the brosertab

</head>#Contains everything visible to users. 
#Examples: Text, Images, Buttons, links etc.

<body>

<p> This is my First Parragraph</p>
<h1> This is Heading 1</h1>
</body>
</html>

#Day 2 : Building the page Structure
Objectives:
By the end of this session
. Understand the importance of semantic HTML
. Use semantic HTML elements to structure a webpage
. Build a complete a wape page layout
. Link multiple HTML pages together
. Create a Simple multi-page website

#Semantic HTML
it uses tags that clearly describe the meaning of their content.These tags make web page easier to read, understand, maintain, and improve accesibility.


#Non-Semantic Elements
These elements don't describe their purpose.
<div>
<span>
Example
<div>
<div> Header </div>
</div>

#Sematic Elements
These elements describe their role in the webpage.

Tag and its purpose
<header>: Top section of the page
<nav>: Navigation Links
<main>: Main content area
<section>: Groups related content
<article>:Independent Content
<aside>: Sidebar Information
<footer>: Bottom Section of the page

#Linking Pages Together
#Large websites containing multiple pages connected through hyperlinks
example
index.html
about.html
contact.html

Task
Build a mini website containing:
index.html
about.html
contact.html
Requirements:

All pages must be linked.
Use semantic HTML elements.
Add headings and paragraphs.
Include a footer on every page.
