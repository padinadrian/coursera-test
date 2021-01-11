# Lecture 3: Anatomy of an HTML Tag

Example:

```
<p> content </p>
```

A tag consists of an element name "p" and the surrounding brackets which make it a tag.

Some tags only have an opening tag and no close tag:
* `<br>` line break

```
<p id="myId"></p>
```

Here id is the Attribute Name and "myId" is the attribute value.

All elements must have a unique id; if two elemnts have the same id, that HTML is invalid.

Must have at least one space between the tag name and the attribute name, but no space is allowed between the opening bracket "<" and the tag name. No attributes are allowed in the closing tag.

Using quotes around the attribute value is not required but it is best practice to use either single or double quotes.

You can mix single and double quotes but you must close with the same kind of quote that you opened. In general you should use the same pattern throughout the page for readability.

Shortcut for a tag that has no content: `<p/>`

Next: Basic HTML document structure.