Heading tags
--------------------
1. h1 to h6 ---> heading tags
2. p --> paragraph

every html element has style.

172.22.253.101:5500/index.html
==============================================================================
1. windows server: html, css, bootstrap, js, asp.net, php 
2. linux server : ReactJS, angular, springboot application

aws , gcp, microsoft azure ---> linux server, python

Hosting Type:
-----------------------------

1. Shared Hosting
2. VPS Hosting(Virtual Private Server)



html can run on browser 
browser --> 1995

1990 ---> WorldWideWeb ---> www --> Nexus  

1992 ---> Line Mode Browser 

1993 --> Mosaic 

1995 --> 
=======================================================================================

Basic Tags in html
------------------------------
1.p : to store static type of information.
2.a : anchor tag--> anchor tag can be used for to nevigate between the pages.
img: 

file:///home/ajinkya/Documents/May_June/pages/adminPage.html
file:///home/ajinkya/Documents/May_June/pages/admin/adminPage.html

Absolute Path
Relative Path

When we take images make sure its size. HD images results in page loading time. For this we need to use another image format called as webp.

3. pre : pre formatted text
4. mark : 
5. strong or b: 
6  itelic [i, em]
7. span: 
8. sup:
9. sub:
10.marquee: can be used to move text from left, right, up, down.
            Attribute : width, height, direction, scrollamount, hspace, vspace, behavior


Sementic Tags
-------------------------
header : company name or menu
footer : copyright, address, map, social media links, temrs and conditions, privacy and policy
nav  : menu (simple menu or dropdown menu)
section : it is the replacement for div.
main : it is the replacement for body tag
article : it is small section which are present in web.
aside : it is called as sidebar 
audio : to impiment audio in my page. mp3/ ogg/ wav
video : To represent our company information, short news about success, 

Sementic tags can be used for to achive SEO(Search engine optimization).
By using Sementic we can maintain the code readability.
===================================================================

OL and UL
-----------------
Basically this tag can be used for to make the menu. 
1. Simple menu
2. Dropdown menu 

UL:(Unordered List)
------------------------
1. UL tag contains the unordered list which means there is no sequance number present.
2. By default the type of UL tag is bullets.
3. UL tags contains numbers of li tag.
4. html5 dont support the attribute called type for UL.
5. The attribute type can be used for to change the bullets into various types.
6. You can handle type by using css property.
    1. list-style-type : none, disc, square, circle
    2. list-style-image: url(path)
7. Nesting of UL:
-----------------------
Nested concept can be used for to make the menu dropdown.

OL(Ordered List):
-----------------------------
1. In this tag there will be sequance of number are present.
2. In html5 the type attribute supported by OL tag.
3. In OL tag we use different types of type attribute.
    type : roman number, alphabets, numbers 
    start : it will always number
    reverse: it will print the number in reverse order


===================================================================


Tables in html
--------------------
1. The table tag can be used for to display the data in proper format.
2. Table contains the rows and columns.
3. In 2005, table tag was used for to desgin the layout of html.
4. later there was problem that is we cant make the pages responsive, bcz table tag not supported for responsiveness.
5. In html5 suppose i want to use table tag than i have tag called <table></table>
6. In table tag there will be number of another tags are present like,
    a) table
    b) thead : It is group of th tags.
    c) th : table heading(Column name)
    d) tr : table row which contains table data(information like name, age, email)
    e) td : Which contains actual data or records.
    f) tbody: It is the group of <tr></tr> and <td></td>
    g) caption: It indicates the name of the table.
Note:
----------
<table width, border, cellsspacing, cellsPadding>
    In above table all the attribute are removed from html5
</table>

rowspan
colspan


Image Mapping
--------------------
To create the clickable areas on image.
To create image map in html we use two tags
    a) map 
    b) area 
    

Form Tags in html
---------------------
The form tag can be used for to collect the user data.
In html we can use the form tag as below

Example
--------------
<form>

</form>

The form tag has following attribute,
a) action : page url or endpoint
b) method: http method --> get, post, put, delete, patch
c) enct-type : media --> images, video, audio, pdf, .txt, .docx --> form/data
d) accept-charset --> utf-8
e) name



login.php 
login.html

login.ejs
login.js 

status code 200, 201,400, 401

url : http://localhost:7878/login --> endpoint

Form tags
-----------------------------
label : it will display static text
input : on the basis of requirement we change the input type like, text, radio, email
number, date


Form : Employee Registration
------------------------------------
Fields
------------
name
age
gender
birthdate
email
mobile
skills
country --> dropdown box --> select tag --> options
city
address --> textarea tag
upload photo

open file dialog box 
save file dialog box
font dialog box
color dialog box 
print dialog box 


========================================================================================================================================================
CSS Introduction
====================================================
What is css?
----------------------------------
CSS is nothing but it cascadeing stylesheet programming langauge.
It was introduced in the year of 1995, by Hackon Lie.
CSS3 is the combination of CSS + JS.
The first of version of css is called as css level1 in the year of 1996.
After the 2yr that is 1998, next version of css came in market and which was known as CSS Level2.
After 10yrs that is 2008, latest css was introduced which was known as CSS3.


Why we use the css?
-------------------------------------------
As we know, the element of html is ugly in nature.
So, we change the nature of html element we use the css to make them very attractive as well as make the web app responsive in nature.

What are the different types of css are present?
----------------------------------------------------------
As we know there are 3 types of css are present,
a) inline css:
--------------------------
In this type of css we can write the property inside the html element by using the tag called as <style></style>.
Note: Each element in html has the style.


b) internal css:
------------------------------
In this type of css we can write the css property inside the html page, which is located in <head></head> section using the tag called <style></style>.


c) external css:
-------------------------------
In this type css we can write the css property inside the external file which is located in our project root directory.
When write css property inside the external file dont use the <style></style>.
The external file has the extension called as .css 
We link the external css with html page we use the tag called as <link></link>. Inside the link tag we pass some attribute rel means relation with stylesheet and than another attribute called as href which denote the location of css file.

Example:
------------------
<link rel="stylesheet" href="./css/style.css" />

The general syntax of css is as below,

selectors{
    key:value,
    key:value
}



Q. What is mean by selectors in css and explain its types?
----------------------------------------------------------------------------
Def : Selectors is nothing but targetting element.

Types of selectors:
-----------------------------
1. id selectors : It is indicated by # symbol. It is unique.
2. class selector : It is indicated by using .(dot). We can apply multiple classes to single element.
3. tag with class selector
4. tag selector : We can directly target html element like h1, p, div, body, table, ul, li etc ....
5. group selector :  We can create a group also like h1,h2 this one group than h5,h6 another group.
6. universal selector : It is indicated by using * symbol.
7. psudeo classes and psudeo elements


psudeo elements:
------------------------------
1. ::After
2. ::before
3. ::selection
4. ::first-line
5. ::placeholder
6. ::first-letter



Q. How we can declare the variables in css?
-------------------------------------------------------
In css we can declare the variables using the global scope.
In css the global scope declared by using psudeo class :root
The variables are created using --variable_name.
We can acees the variables using the function called as var().
Example:
--------------------
var(--variable_name)


Q. What is mean @import rule?
---------------------------------------------
If i have multiple css files and i want to add these files into a main css file than we can use
@import rule.



