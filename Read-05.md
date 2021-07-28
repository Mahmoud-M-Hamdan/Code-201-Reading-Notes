# Html
## Adding Images
To add an image into the page
you need to use an img
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:

***src***
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).

***alt***
This provides a text description
of the image which describes the
image if you cannot see it.

***title***
You can also use the title
attribute with the img element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.
Adding Images
The text used in the alt attribute
is often referred to as alt text.
It should give an accurate
description of the image content
so it can be understood by
screen reader software (used by
people with visual impairments)
and search engines.
If the image is just to make a
page look more attractive (and
it has no meaning, such as a
graphic dividing line), then the
alt attribute should still be used
but the quotes should be left
empty.

## Height & Width of Images

You will also often see an img
element use two other attributes
that specify its size:

***height***
This specifies the height of the
image in pixels.

***width***
This specifies the width of the
image in pixels.
Images often take longer to
load than the HTML code that
makes up the rest of the page.
It is, therefore, a good idea to
specify the size of the image
so that the browser can render
the rest of the text on the page
while leaving the right amount of
space for the image that is still
loading.
The size of images is increasingly
being specified using CSS rather
than HTML

## Three Rules for Creating Images

1.
Save images in
the right format
Websites mainly use images in
jpeg, gif, or png format. If you
choose the wrong image
format then your image might
not look as sharp as it should
and can make the web page
slower to load.
2.
Save images at
the right size
You should save the image at
the same width and height it will
appear on the website. If
the image is smaller than the
width or height that you have
specified, the image can be
distorted and stretched. If the
image is larger than the width
and height if you have specified,
the image will take longer to
display on the page.
3.
Use the correct
resolution
Computer screens are made up
of dots known as pixels. Images
used on the web are also made
up of tiny dots. Resolution refers
to the number of dots per inch,
and most computer screens only
show web pages at 72 pixels
per inch. So saving images at
a higher resolution results in
images that are larger than
necessary and take longer to
download.

# Css

## color

The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:

***rgb values***
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)

***hex codes***
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80

***color names***
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan
We look at these three different
ways of specifying colors on the
next double-page spread.
CSS3 has also introduced
another way to specify colors
called HSLA, which you will
meet near the end of this chapter
on page 255-256.
Foreground Color

***color***
Above each CSS rule in this
example you can see how CSS
allows you to add comments
to your CSS files. Anything
between the /* symbols and
the */ symbols will not be
interpreted by the browser.
They are shown in grey above.
The use of comments can help
you to understand a CSS file
(and organise it, by splitting a
long document into sections).
Here, we have used comments
to indicate which method is used
to specify each of the different
types of colors.

## Background Color

CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names
(covered on the next page).
If you do not specify a
background color, then the
background is transparent.
By default, most browser
windows have a white
background, but browser users
can set a background color for
their windows, so if you want
to be sure that the background
is white you can use the
background-color property on
the body element.

***RGB Values***
Values for red, green, and blue
are expressed as numbers
between 0 and 255.

***Hex Codes***
Hex values represent values
for red, green, and blue in
hexadecimal code.

***Color Names***
Colors are represented by
predefined names. However,
they are very limited in number.

***Hue***
Hue is near to the colloquial idea
of color. Technically speaking
however, a color can also have
saturation and brightness as
well as hue.

***Saturation***
Saturation refers to the amount
of gray in a color. At maximum
saturation, there would be no
gray in the color. At minimum
saturation, the color would be
mostly gray.

***Brigh tness***
Brightness (or "value") refers
to how much black is in a color.
At maximum brightness, there
would be no black in the color.
At minimum brightness, the
color would be very dark.

