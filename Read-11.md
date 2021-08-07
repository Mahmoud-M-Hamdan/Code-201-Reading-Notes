# Html

## Controlling sizes of images in CSS

You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.


Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.


You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages.


For example, an e-commerce site
tends to show product photos
at the same size. Or, if your site
is designed on a grid, then you
might have a selection of image
sizes that are commonly used on
all pages, such as:
Small portrait: 220 x 360
Small landscape: 330 x 210
Feature photo: 620 x 400
Whenever you use consistently
sized images across a site,
you can use CSS to control
the dimensions of the
images, instead of putting the
dimensions in the HTML.


First you need to determine the
sizes of images that will be used
commonly throughout the site,
then give each size a name.


For example:
small
medium
large
Where the <img> elements
appear in the HTML, rather
than using width and height
attributes you can use these
names as values for the class
attribute.



In the CSS, you add selectors for
each of the class names, then
use the CSS width and height
properties to control the image
dimensions.


## AligNi ng images Using CSS

In the last chapter, you saw how
the float property can be used
to move an element to the left or
the right of its containing block,
allowing text to flow around it.
Rather than using the img
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:
1: The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).
2: New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.
In this example you can see the
align-left and align-right
classes used to align the image.
It is also common to add a
margin to the image to ensure
that the text does not touch their
edges.




## Centering images Using CSS

By default, images are inline
elements. This means that they
flow within the surrounding text.
In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.
Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:
1: On the containing element,
you can use the text-align
property with a value of center.


2: On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.


You can specify class names
that allow any element to be
centered, in the same way that
you can for the dimensions or
alignment of images.



## background-image

The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.
The path to the image follows
the letters url, and it is put
inside parentheses and quotes.
Here is the image
tile used in this
example.

In the first example, you can
see a background image being
applied to an entire page
(because the CSS selector
applies to the body element).
In the second example, the
background image just applies to
a paragraph.
If you search online, you will
find lots of resources that offer
background textures that you
can use on your pages.



## shorthand background

The background property acts
like a shorthand for all of the
other background properties
you have just seen, and also the
background-color property.
The properties must be specified
in the following order, but you
can miss any value if you do not
want to specify it.


1: background-color
2: background-image
3: background-repeat
4: background-attachment
5: background-position
CSS3 will also support the use
of multiple background images
by repeating the background
shorthand. Because few
browsers supported this
property at the time of writing, it
was not commonly used.


div {
background:
url(example-1.jpg)
top left no-repeat,
url(example-2.jpg)
bottom left no-repeat,
url(example-3.jpg)
centre top repeat-x;}
The first image is shown on top,
with the last one on the bottom.

Using CSS, it is possible to create
a link or button that changes to a
second style when a user moves
their mouse over it (known as a
rollover) and a third style when
they click on it.
This is achieved by setting a
background image for the link or
button that has three different
styles of the same button (but
only allows enough space to
show one of them at a time).
You can see the image we are
using in this example on the
right. It actually features two
buttons on the one image.
When the user moves their
mouse over the element, or
clicks on it, the position of the
background image is moved to
show the relevant image.
When a single image is used
for several different parts of an
interface, it is known as a sprite.
You can add the logo and other
interface elements, as well as
buttons to the image.
The advantage of using sprites is
that the web browser only needs
to request one image rather than
many images, which can make
the web page load faster.
