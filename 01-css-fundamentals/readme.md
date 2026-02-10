# CSS Fundamentals

## what is css?

CSS, or “Cascading Style Sheets,” is a styling language used to give visual presentation and organize layout.

## What is CSS used for?

CSS is used to give visual presentation or organize the layout, it can also control how users perceive information.

## Difference between structure (HTML) and presentation (CSS)

HTML defines what everything is. It answers questions like: Is this a title? Is this a form?
CSS answers questions like: What color is this? Does this go at the top or the bottom?
HTML is the structure and CSS is the visual presentation.
CSS is dependent on HTML, but HTML can function without CSS.

## How the browser processes HTML + CSS

The browser downloads and parses the HTML to build the DOM; at the same time, it downloads and parses the CSS to build the CSSOM; then it combines them in the render tree, calculates the layout, and paints the screen.

## What is a style sheet?

A style sheet is a document that typically has a .css extension and defines the visual presentation of an HTML document. This allows the visual presentation to be separated from the content.

## What is a CSS rule?

It is an instruction that tells you what (selector) to apply something (property) to.
It literally means: do this to this.

## What happend when there are erros in the CSS?

The browser ignores what is wrong and continues with what it does understand.

# best practices

## separate style from structure

It is good practice because it separates responsibilities between visual presentation and content, which makes the code more readable, easier to maintain, and less fragile to design changes.

## Do not use inline CSS in HTML

The use of inline CSS is not good practice, as it mixes structure with visual presentation, reduces the readability of HTML, and makes project maintenance and scalability more tedious and fragile.

## Do not overuse IDs.

Not overusing IDs is good practice because IDs are unique and highly specific, which makes reuse difficult, makes CSS rigid, and reduces the scalability of the project.

## think in blocks

Think in blocks rather than loose content; organize your mind in a literal way to work better.

## keep CSS legible

Is good practice because it facilitates understanding, improves reading speed, and allows you to read aloud without fear.
