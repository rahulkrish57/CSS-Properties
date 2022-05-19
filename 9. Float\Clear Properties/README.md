# float Property
The float property is used for positioning and formatting content e.g. let an image float left to the text in a container.

The float property can have one of the following values:
#### left
The element floats to the left of its container
#### right
The element floats to the right of its container
#### none
The element does not float (will be displayed just where it occurs in the text). This is default.
#### inherit
The element inherits the float value of its parent

In its simplest use, the float property can be used to wrap text around images.
# clear Property
When we use the float property, and we want the next element below (not on right or left), we will have to use the clear property.

The clear property specifies what should happen with the element that is next to a floating element.

The clear property can have one of the following values:

#### none
The element is not pushed below left or right floated elements. This is default
#### left
The element is pushed below left floated elements
#### right
The element is pushed below right floated elements
#### both
The element is pushed below both left and right floated elements
#### inherit
The element inherits the clear value from its parent

When clearing floats, you should match the clear to the float: If an element is floated to the left, then you should clear to the left. Your floated element will continue to float, but
the cleared element will appear below it on the web page.
