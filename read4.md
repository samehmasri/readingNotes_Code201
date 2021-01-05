# **HTML**
# links 

> URL: stands for Uniform Resource Locator

# Relative URL 
> Relative URLs can be used when linking to pages within your own
website. They provide a shorthand way of telling the browser where to
find your files.
## relative links type
1. **Same Folder** To link to a file in the same folder, just use the file
name. (Nothing else is needed.).

2. **Child Folder** For a child folder, use the name of the child folder,
followed by a forward slash, then the file name.

3. **Grandchild Folder** Use the name of the child folder, followed by a
forward slash, then the name of the grandchild folder, followed by another forward slash, then the
file name.

4. **Parent Folder** Use ../ to indicate the folder above the current one,
then follow it with the file name.

5. **GrandParent Folder** Repeat the ../ to indicate that you want to go up
two folders (rather than one), then follow it with the
file name.

**LINKS can be divided to three sections:**

1. Creating links between pages in the same site:

* when we want to link our website to internal pages we don't have to specify the domain name in the URL
<a href="index.html">Home</a></li>, that means when creating your own web page you need to code multi-HTML pages with in the same site and link them to each other using the <a tag> like I showed you earlier.


2. Linking to other sites:

* first of all the links in HTML are created using an element: <a herf="http:/www.website.com">meaning full name of the link</a>
* when using the previous element the color of the link that u add to another site will be blue indicating that its a link to help the user to surfe your site easier 

3. Email links: this links used to send a email to the website owner its written as following:
Ex: <a href="mailto:jon@example.org">Email Jon</a>

4. Opening Links in a New Window:
code written as following : <a href="http://www.imdb.com" target="_blank">

**target attribute**  is used to open the link in onther window the browser that your using.

5. Linking to a Specific Part of the Same Page:
in order to use this you at first to give id to each element you want to refer to in order to use the linking attribute to make easier for the user to navegate through your site here is an example:
Ex: 
* <h1 id="top">Film-Making Terms</h1>
<a href="#arc_shot">Arc Shot</a><br />
<a href="#interlude">Interlude</a><br />
<a href="#prologue">Prologue</a><br /><br />
<h2 id="arc_shot">Arc Shot</h2>
<p>A shot in which the subject is photographed by an
encircling or moving camera</p>
<h2 id="interlude">Interlude</h2>
<p>A brief, intervening film scene or sequence, not
specifically tied to the plot, that appears
within a film</p>
<h2 id="prologue">Prologue</h2>
<p>A speech, preface, introduction, or brief scene
preceding the the main action or plot of a film;
contrast to epilogue</p>
<p><a href="#top">Top</a></p>

6. Linking to a Specific Part of Another Page:
its same as before but the section in the other page has to have an id so you can refer back to it

# Directory Structure
> On larger websites it's a good idea to organize your code by placing the
pages for each different section of the site into a new folder. Folders on a
website are sometimes referred to as directories.

# **Css**
# positioning schemes:

1. Normal flow:
* Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside,
they will not appear next
to each other. This is the default
behavior

2. Relative Positioning:
* This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.

3. Absolute positioning:
* This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page.

> Box offset
# Fixed Positioning

* This is a form of absolute
positioning that positions
the element in relation to the
browser window, as opposed
to the containing element.
Elements with fixed positioning
do not affect the position of
surrounding elements and they
do not move when the user
scrolls up or down the page. 

# Floating Elements

* Floating an element allows
you to take that element out
of normal flow and position
it to the far left or right of a
containing box. The floated
element becomes a block-level
element around which other
content can flow.

# screen size 

* different users has different screen sizes so you should consider this in your design. 

# screen resolution 

* Resolution refers to the number of dots a screen shows per inch. Some
devices have a higher resolution than desktop computers and most
operating systems allow users to adjust the resolution of their screens.

# page size 

* since screen sizes and resolution vary from one device to another,
web designers use's a range from 960-1000 px.



# javascripts 

* A script is made up of a series of statements. Each
statement is like a step in a recipe.

* Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value.

* Variables are used to temporarily store pieces of
information used in the script.

# functions, methods, objects

> functions : a group of statements that perform specific task, also functions help you to not repeat a code.
* for creating a function you need to give a name then open {} then inside the bracets you enter the code that does a specific task.
* for calling a function all you need to do is to write the function name and add a () after it

# pairing programming

* ***benfits:*** 
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students or co-workers
4. Social skills
5. Job interview readiness
6. Work environment readiness