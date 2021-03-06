# Lecture 7: Lists

Lists allow you to group related content. Think of a todo list, shopping list, etc.

Example:

```
<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item
    <ul>
    <li>Subitem A</li>
    <li>Subitem B</li>
    </ul>
<li>Fourth item</li>
</ul>
```

Looks like this:

<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item
    <ul>
    <li>Subitem A</li>
    <li>Subitem B</li>
    </ul>
<li>Fourth item</li>
</ul>

## Tags

`<ul>` stands for Unordered List.
`<li>` stands for List Item.

In an unordered list, by default the items are listed as bullet points.

Only `<li>` elements can be in a `<ul>` block (NO TEXT ALLOWED).

`<ol>` stands for Ordered List. In an ordered list, items are listed as numbers.

Example:

```
<ol>
<li>Step 1</li>
<li>Step 2</li>
<li>Step 3
    <ol>
    <li>Substep A</li>
    <li>Substep B</li>
    </ol>
<li>Step 4</li>
</ol>
```

Looks like this:

<ol>
<li>Step 1</li>
<li>Step 2</li>
<li>Step 3
    <ol>
    <li>Substep A</li>
    <li>Substep B</li>
    </ol>
<li>Step 4</li>
</ol>