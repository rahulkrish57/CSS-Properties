# static www.google.com
static It is the default position value for the element. Under static position, elements positioned according to the normal flow of the page.
#### Note:
 left, right, top, and bottom properties will not affect if position is static.

# relative
Relative In this case, the element remains in the normal flow of the document but left, right, top, and bottom affects. Elements get shifted from their original position in the document creating vacant space and other elements may adjust themselves according to the vacant space left by the element.

# absolute
absolute Absolute elements do not follow the normal flow document instead they position themselves relative to the closest positioned ancestor. Its final position is determined using the top, bottom,  left and right.
#### Note:
The positioned element means element having position property other than static..

# fixed
fixed means fixed to the viewport. We provide the position values (top, bottom, right, or left) and the element stays there when the user is scrolling. No matter what is happening on screen the fixed element will not move at all.

# sticky
sticky means the element will scroll until it reaches the offset value given to it by the user and then stays in its position. Sticky element always stays within its parent block and as soon as the parent block leaves the screen as an effect of scrolling, sticky elements also leave with it.
