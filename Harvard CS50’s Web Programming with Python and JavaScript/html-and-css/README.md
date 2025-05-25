# Harvard CS50’s Web Programming with Python and JavaScript

## HTML and CSS

### HTML - HyperText Markup Language
HTML is used to describe the structure of the page. We can think about an HTML page in terms of a tree like structure that we call DOM (Document Object Model). DOM describes how all of HTML elements are related to each other.

### CSS - Cascading Style Sheets
CSS is used to add styles to the HTML


#### CSS Selectors

- a, b -> Multiple Element Selector
- a b -> Descendant Selector
- a > b -> Child Selector
- a + b -> Adjacent Sibling Selector
- [a=b] -> Attribute Selector.
    - [type=text] -> Selects input elements with type text
    - [href^=https] -> Selects links that start with https
    - [href$=.pdf] -> Selects links that end with .pdf
    - [href*=example] -> Selects links that contain the word example
- a:b -> Pseudo-class Selector.
    - :hover -> Selects an element when the mouse hovers over it
    - :focus -> Selects an element when it has focus
    - :active -> Selects an element when it is being activated by the user
    - :visited -> Selects links that have been visited
    - :link -> Selects links that have not been visited
- a::b -> Pseudo-element Selector. 
  - ::before -> Insert content before the element
  - ::after -> Insert content after the element
  - ::first-letter -> Selects the first letter of an element
  - ::first-line -> Selects the first line of an element
