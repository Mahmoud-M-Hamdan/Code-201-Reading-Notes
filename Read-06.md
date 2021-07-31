# JS
## WHAT IS AN OBJECT?
***Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.***

IN AN OBJECT: VARIABLES BECOME
KNOWN AS PROPERTIES
If a variable is part of an object, it is called a
property. Properties te ll us about the object, such as
the name of a hotel or the number of rooms it has.


Each individual hotel might have a different name
and a different number of rooms.


IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS METHODS
If a function is part of an object, it is called a method.
Methods represent tasks that are associated with
the object. For example, you can check how many
rooms are available by subtracting the number of
booked rooms from the total number of rooms.

This object represents a hotel. It has five properties and one method.
The object is in curly braces. It is stored in a variable called hotel .
Like variables and named functions,
properties and methods have a
name and a va lue. In an object,
that name is called a key.


An object cannot have two keys
with the same name. This is
because keys are used to access
their corresponding values.


The value of a property can be a
st ring, number, Boolean, array, or
even another object. The va lue of a
method is always a function.


## The Document Object Model (DOM)

* The browser represents the page using a DOM tree.
DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.
* You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.
* Whenever a DOM query can return more than one
node, it will always return a Nadel i st.
* From an element node, you can access and update its
content using properties such as textContent and
* i nnerHTML or using DOM manipulation techniques.
* An element node can contain multiple text nodes and
child elements that are siblings of each other.
* In older browsers, implementation of the DOM is
* inconsistent (and is a popular reason for using jQuery).
* Browsers offer tools for viewing the DOM tree .