# basic selectors

## Type selector

They are selectors that apply the same styles to all elements that correspond to the same tag; they have low specificity, lower than that of a #id or a .class.

## Class selector

The class selector is a selector that applies the desired change to every class that has a specific name. There can be many classes within a single class attribute, it is reusable without limit, and many different elements can respond to the same name.

## ID selector

The ID selector is a highly specific selector that must be unique across the entire page. It is used to indicate that the change will be applied to this element and absolutely nothing else. It has very high specificity, surpassed only by inline CSS and !important.

## Class vs ID difference

The class selector targets elements and has the advantage of being reusable; many elements with the same class name can apply the changes defined in CSS for that class. The ID selector is highly specific and must be unique across the entire page; it is not reusable and has higher specificity than a class. In professional practice, classes are used more frequently than IDs, as classes provide better long-term scalability.

## Rules for proper use

class should be used for reusable styles
class can be repeated unlimited times in the document
class can have multiple classes within a single element

id must be unique throughout the entire document
two elements cannot have the same ID
an element cannot have two IDs

## Common mistakes with classes and IDs

Mistakes with class:
Generic names without intention
Chaining too many classes
Using a class for something clearly unique

Mistakes with ID:
Repeating the same ID
Using an ID for reuse
Using an ID just because it has higher specificity
Basing the entire structure on IDs

## Basic naming conventions

Do not mix languages
Avoid vague names
Avoid names that depend on visual appearance
It is recommended to use the BEM methodology “block\_\_element--modifier”
Name by intention, not by appearance.
