# CSS-oriented DOM

## the DOM or (Document Object Model)

it is the way the browser moves effectively through documents. in CSS the CSSOM is used, using a tree where each tag will be a node in the tree, being represented as parent, child, grandchild

Example 1:

body
└section
└p

section - child of body
p - child of section
p - descendant of body

important things:
i should only memorize 3 relationships,

(1) parent:
section
└ P

section is parent

(2) child:
div
└ p

p is child of div

(3) descendant:
section
└ div
└ span
span is descendant, any element inside

## in conclusion

The Document Object Model is a tree-like structure that the browser creates from HTML, where each element is a node with hierarchical relationships (parent, child, descendant and siblings).
CSS uses that structure to locate elements through selectors, apply styles according to their position in the tree and allow certain properties to be inherited along those relationships.
