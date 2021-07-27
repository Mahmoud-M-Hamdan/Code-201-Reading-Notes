# Html
## Links
Links are created using the a element. Users can click on anything
between the opening a tag and the closing a tag. You specify
which page you want to link to using the href attribute.
The text between the opening
a tag and closing a tag
is known as link text. Where
possible, your link text should
explain where visitors will be
taken if they click on it (rather
than just saying "click here").
Below you can see the link to
IMDB that was created on the
previous page.


Many people navigate websites
by scanning the text for links.
Clear link text can help visitors
find what they want. This
will give them a more positive
impression of your site and may
encourage them to visit it for
longer. (It also helps people
using screen reader software.)



To write good link text, you can
think of words people might
use when searching for the
page that you are linking to.
(For example, rather than write
"places to stay" you could use
something more specific such as
"hotels in New York.")
### Linking to Other Sites
Links are created using the a
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.
Users can click on anything that
appears between the opening
a tag and the closing a
tag and will be taken to the page
specified in the href attribute.
When you link to a different
website, the value of the href
attribute will be the full web
address for the site, which is
known as an absolute URL.

### Linking to Other Pages on the Same Site

When you are linking to other
pages within the same site,
you do not need to specify the
domain name in the URL. You
can use a shorthand known as a
relative URL.

If all the pages of the site are in
the same folder, then the value
of the href attribute is just the
name of the file.

If you have different pages of a
site in different folders, then you
can use a slightly more complex
syntax to indicate where the
page is in relation to the current
page. You will learn more about
these on the pages 81-84.

If you look at the download
code for each chapter, you will
see that the index.html file
contains links that use relative
URLs.

## Layout

### Key Concepts in Positioning Elements



Building Blocks
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors.

Containing Elements
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
It is common to group a number of elements together inside a <>
(or other block-level) element. For example, you might group together
all of the elements that form the header of a site (such as the logo and
the main navigation). The <> element that contains this group of
elements is then referred to as the containing element.

# JS

## WHAT IS A FUNCTION?
**Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements)** 
Grouping together the The steps that the function On the right, there is an example
statements that are required to needs to perform in order to of a function in the JavaScript
answer a question or perform a perform its task are packaged file. It is called updateMessage () .
task helps organize your code. up in a code block. You may
remember from the last chapter Don't worry if you do not
Furthermore, the statements in a that a code block consists of one understand the syntax of the
function are not always executed or more statements contained example on the right; you will
when a page loads, so functions within curly braces. (And you do take a closer look at how to wri te
also offer a way to store the steps not write a semicolon after the and use functions in the pages
needed to achieve a task. The closing curly brace - like you do that follow.
script can then ask the function after a statement.)
to perform all of those steps as Remember that programming
and when they are required. Some functions need to be languages often rely upon on
For example, you might have provided with information in name/value pairs. The function
a task that you only want to order to achieve a given task. For has a name, updateMessage,
perform if the user clicks on a example, a function to ca lculate and the value is the code block
specific element in the page. the area of a box would need (which consists of statements).
to know its width and height. When you call the function by its
If you are going to ask the Pieces of information passed name, those statements will run.
function to perform its task to a function are known as
later, you need to give your parameters. You can also have anonymous
function a name. That name functions. They do not have a
should describe the task it is When you write a function and name, so they cannot be called.
performing. When you ask it to you expect it to provide you Instead, they are executed as
perform its task, it is known as with an answer, the response is soon as the interpreter comes
ca lling the function. known as a return value. across them.

## A BASIC FUNCTION
 the user is
shown a message at the top of
the page. The message is held
in an HTML element whose id
attribute has a value of message.
The message is going to be
changed using JavaScript.

Before the closing 
tag, you can see the link to the
JavaScript file. The JavaScript
file starts with a variable used
to hold a new message, and is
followed by a function ca lled
updateMessage().

You do not need to worry about
how this function works yet - you
will learn about that over the
next few pages. For the moment,
it is just worth noting that inside
the curly braces of the function
are two statements.


