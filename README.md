# CSS-Properties
# CSS Box Model
#### Padding
#### Margin
#### Border
# CSS-Outline-Propety
An outline is a line drawn outside the element's border.
# CSS Display Properties
## block
Always starts a new line and takes full width
## inline
Does not start a new line and only take up as much as content space
## horizontal centering
To horizontally center a block element (like <div>), use margin: auto; Setting the width of the element will prevent it from stretching out to the edges of its container.
# inline-block
with display: inline-block, the top and bottom margins/paddings are respected, but with display: inline they are not.
# border-box
The width and height properties (and min/max properties) includes content, padding and border.
# display: none, opacity, visibility
## display: none
commonly used with JavaScript to hide and show elements without deleting and recreating them
## opacity
The opacity property can take a value from 0.0 - 1.0. The lower value, the more transparen
## visibility
The visibility property specifies whether or not an element is visible
# background-image Property
The background-image property sets one or more background images for an element.
The background of an element is the total size of the element,
including padding and border (but not the margin).
Always set a background-color to be used if the image is unavailable.
# background-position Property
The background-position property sets the starting position of a background image.
By default, a background-image is placed at the top-left corner of an element,
and repeated both vertically and horizontally.
# background-attachment Property
The background-attachment property sets whether a background image scrolls with the rest of the page, or is fixed.
# linear-gradient() Property
To create a linear gradient you must define at least two color stops. Color stops are the colors you want to render smooth transitions among. You can also set a starting point and a direction (or an angle) along with the gradient effect.
### colorzilla
https://www.colorzilla.com/gradient-editor/
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
# static
Static It is the default position value for the element. Under static position, elements positioned according to the normal flow of the page.
#### Note:
 left, right, top, and bottom properties will not affect if position is static.

# relative
Relative In this case, the element remains in the normal flow of the document but left, right, top, and bottom affects. Elements get shifted from their original position in the document creating vacant space and other elements may adjust themselves according to the vacant space left by the element.

# absolute
Absolute elements do not follow the normal flow document instead they position themselves relative to the closest positioned ancestor. Its final position is determined using the top, bottom,  left and right.
#### Note:
The positioned element means element having position property other than static..

# fixed
fixed means fixed to the viewport. We provide the position values (top, bottom, right, or left) and the element stays there when the user is scrolling. No matter what is happening on screen the fixed element will not move at all.

# sticky
sticky means the element will scroll until it reaches the offset value given to it by the user and then stays in its position. Sticky element always stays within its parent block and as soon as the parent block leaves the screen as an effect of scrolling, sticky elements also leave with it.
# media queries
allow you to create different layouts depending on the size of the viewport
# CSS Selectors
## Descendant
Descendant selector is used to select all the elements which are child of the element (not a specific element). It select the elements inside the elements i.e it combines two selectors such that elements matched by the second selector are selected if they have an ancestor element matching the first selector.
## Child
Child Selector is used to match all the elements which are child of a specified element. It gives the relation between two elements. The element > element selector selects those elements which are the children of specific parent. The operand on the left side of > is the parent and the operand on the right is the children element.
## ::first-line and ::first-letter
The pseudo-classes :first-line and first-letter are for giving special styles to the first line and letter of an HTML element.
## link, visited, hover, active
### a:link
a normal, unvisited link
### a:visited
a link the user has visited
### a:hover
a link when the user mouses over it
### a:active
a link the moment it is clicked
## :root
The :root selector matches the document's root element. In HTML, the root element is always the html element.
# CSS Transform
## translate()
The translate CSS property allows you to transfer an element from one place to another along the X (horizontal) axis, the Y (vertical) axis, and the Z (depth) axis, similar to how you might think of moving an element using offsets, like top , bottom , left , and right.
## scale()
The scale property in CSS resizes an element’s width and height in proportion.
## rotate()
The CSS rotate() function skews an element by a certain number of degrees. You can rotate an element clockwise using a positive number of degrees. Or, you can rotate an element anti-clockwise using a negative number.
## skew()
The skew() function is an inbuilt function which is used to transform an element in the 2D plane
## CSS Transition
CSS transitions allows you to change property values smoothly, over a given duration.
# CSS Animations
An animation lets an element gradually change from one style to another.
## The @keyframes Rule
When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.

To get an animation to work, you must bind the animation to an element.
