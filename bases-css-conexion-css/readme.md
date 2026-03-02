# CSS Connection

## external CSS (<link>)

External CSS is a separate document from the HTML that is connected from the head of the document with a <link> to define appearance and separate content from visual presentation.

## Internal CSS (<style>)

Internal CSS is writing CSS inside the HTML using the <style> tag, applying styles only to that document with no real possibility of reuse.

## inline CSS (style="")

It is using CSS attributes directly within the HTML, applying changes only to that specific element.

## wich one to use and why

The standard and professional approach is external CSS; it scales and functions the best.

## Priority among the methods

Under equal conditions, the hierarchy is Inline CSS > Internal CSS > External CSS, with inline styles taking precedence over the others.

## Where to place the <link> and why

It must be placed in the head of the HTML document because the browser needs to parse the CSS before rendering the content, thus preventing the FOUC (Flash of Unstyled Content) effect.

## Common mistakes when linking CSS

Most errors when linking CSS are not language-related issues, but mistakes in file paths, naming, or project structure.
