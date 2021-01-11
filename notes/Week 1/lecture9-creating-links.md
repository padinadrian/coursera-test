# Lecture 9: Creating Links

Links are what makes the web what it is!

Example link:

`<a href="www.google.com" title="click for google!"> Linking to an external website.</a>`

Result:

<a href="http://www.google.com" title="link to google">Linking to an external website.</a>

The `a` tag is both a Flow content and a Phrasing content (both an inline element and a block-level element at the same time). The reason for this is to make any kind of element be clickable - including images, text, buttons, etc.

`target` attribute - when set to "_blank" it forces it to open a link in a new tab or window.

Link to a subsection: `href="#section-name"`

This will link to the element with the following:
* An element with the id `section-name`.
* An anchor tag (`<a>`) with a name attribute.

