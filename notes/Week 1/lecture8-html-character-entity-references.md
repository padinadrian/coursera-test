# Lecture 8: HTML Character Entity References

3 Characters You Should Always Escape:

* `<` -- instead use `&lt;` (less-than)
* `>` -- instead use `&gt;` (greater-than)
* `&` -- instead use `&amp;` (ampersand)

Example:

```
Don't be afraid to be &lt; 100% accurate.
```

Result:

Don't be afraid to be &lt; 100% accurate.

Example:

Copyright symbol: `&copy;`

Result: &copy;

Non-breaking space: `&nbsp;` this is a space that will never wrap lines.

Misuse of Entity Reference: don't use `&nbsp;` to add extra spaces - use a span with a margin attribute instead!

Instead of using quotes, you can use `&quote;` to render the " symbol.

Example: Hello, my &quot;friend&quot;