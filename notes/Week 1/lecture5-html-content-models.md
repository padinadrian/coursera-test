# Lecture 5: HTML Content Models

Content Model means which elements are allowed to be nested inside other elements.

HTML5 has 7 different content models

2 Traditional models:
1. Block-Level Elements
   * Render to begin on a new line (by default)
   * May contain inline or other block-level elements
   * Roughly translate to Flow Content
2. Inline Elements
   * Render on the same line (by default)
   * Can only contain other inline elements (not block-level)
   * Roughly translate to Phrasing Content

These older models align well with existing CSS rules so it's important to remember this simplified model for reference.

## div and span

`<div>` is the most generic block-level element
`<span>` is the most generic inline element

`<div>` can contain other div and span elements
`<span>` can contain other span elements but not div

Newline characters in HTML are ignored when the page is rendered. The only thing that matters is elements.

More complex categories from HTML5
1. Flow Content (roughly block-level)
2. Phrasing Content (roughly inline)
3. Embedded Content
4. Interactive Content
5. Metadata Content
6. Heading Content
7. Sectioning Content

Summary:
* Compared block-level and inline content
* Not officially part of HTML5 but still useful for understanding layouts
* Roughly equivalent to flow content and phrasing content