# CSS

Q1. What is CSS and how does it work with HTML?

Ans. CSS stands for Cascading Style Sheets. It is used to set the style in web pages that contain HTML elements. It sets the background color, font-size, font-family, color, … etc property of elements on a web page.

Q2. What are selectors and what are their different types?

Ans. CSS selectors are used to "find" (or select) the HTML elements you want to style. -We can divide CSS selectors into five categories: .Simple selectors (select elements based on name, id, class) .Combinator selectors (select elements based on a specific relationship between them) .Pseudo-class selectors (select elements based on a certain state) .Pseudo-elements selectors (select and style a part of an element) .Attribute selectors (select elements based on an attribute or attribute value)

Q3. What is CSS selector specificity and how does it work?

Ans. A CSS selector is the first part of a CSS Rule. It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.

Q4. Describe z-index and how stacking context is formed.

Ans. The z-index is a 3rd dimension part of a web page which allows elements to be placed on top of or behind each other. you can use z-index on elements with position: absolute, position: relative, position: fixed or position: sticky. If the element has position: static (the default value), or some other positioning scheme like a float, then z-index will have no effect..

tacking context is formed by a weighted rule using a the property value of a CSS declaration.

If a z-index property is applied, the stacking order is modified:

Backgrounds and borders of the root element Positioned elements with a z-index of less than 0 Non-positioned, non-floating block elements, in the order they appear in the source code Non-positioned floating elements, in the order they appear in the source code Inline elements Positioned elements, in the order they appear in the source code Positioned elements with z-index of greater than 0.

Q5. Describe BFC (Block Formatting Context) and how it works.

Ans. A block formatting context (BFC) is a part of a visual CSS rendering of a web page. It's the region in which the layout of block boxes occurs and in which floats interact with other elements. A block formatting context is created by at least one of the following: .The root element of the document ( ). .Floats (elements where float isn't none). .Absolutely positioned elements (elements where position is absolute or fixed). .Inline-blocks (elements with display: inline-block). .Table cells (elements with display: table-cell, which is the default for HTML table cells). .Table captions (elements with display: table-caption, which is the default for HTML table captions). .Anonymous table cells implicitly created by the elements with display: table, table-row, table-row-group, table-header-group, table-footer-group (which is the default for HTML tables, table rows, table bodies, table headers, and table footers, respectively), or inline-table. .Block elements where overflow has a value other than visible and clip. .display: flow-root. .Elements with contain: layout, content, or paint. .Flex items (direct children of the element with display: flex or inline-flex) if they are neither flex nor grid nor table containers themselves. .Grid items (direct children of the element with display: grid or inline-grid) if they are neither flex nor grid nor table containers themselves. .Multicol containers (elements where column-count or column-width isn't auto, including elements with column-count: 1). .column-span: all should always create a new formatting context, even when the column-span: all element isn't contained by a multicol container.

Q6. Have you ever used a grid system, and if so, what do you prefer?

Ans. Yes I used. I prefered Bootstrap. .Bootstrap is one of the most prominent front-end grid frameworks, and it's been used for millions of websites across the Internet for a good reason. It's well-designed, intuitive, flexible, and powerful all at the same time. It's a good idea to start using Bootstrap now, even while we collectively await Bootstrap 4!

Q7. Have you used or implemented media queries or mobile specific layouts/CSS?

Ans. Yes I have used media queries.. It uses the @media rule to include a block of CSS properties only if a certain condition is true.

Q8. Explain how a browser determines what elements match a CSS selector.?

Ans. Browsers match selectors from rightmost (key selector) to left. Browsers filter out elements in the DOM according to the key selector and traverse up its parent elements to determine matches.

Q9. Describe pseudo-elements and discuss what they are used for.?

Ans. A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s). For example, ::first-line can be used to change the font of the first line of a paragraph. Note: In contrast to pseudo-elements, pseudo-classes can be used to style an element based on its state.

Q10. Explain your understanding of the box mode.?

Ans. The CSS box model is a container that contains multiple properties including borders, margin, padding, and the content itself. It is used to create the design and layout of web pages. It can be used as a toolkit for customizing the layout of different elements.

Q11. What does * { box-sizing: border-box; } do? What are its advantages?

Ans. The box-sizing property defines how the width and height of an element should be visible to the user i.e. border and padding are to be included or not. Syntax: box-sizing: content-box|border-box;

Q12. What is the CSS display property and can you give a few examples of its use?

Ans. The display CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.

Q13. What's the difference between inline and inline-block?

Ans. Compared to display: inline , the major difference is that display: inline-block allows to set a width and height on the element. Also, with display: inline-block , the top and bottom margins/paddings are respected, but with display: inline they are not.

Q14. What's the difference between the "nth-of-type()" and "nth-child()" selectors?

Ans. nth-child() Selector: This selector is used to match the elements based on their position in a group of siblings. It matches every element that is the nth-child, regardless of the type, of its parent.

Syntax: :nth-child(number) { // CSS Property }

nth-of-type() Selector: This Selector is used to style only those elements which are the nth number of children of its parent element. Any n may be a number, a keyword, or a formula.children

Syntax: :nth-of-type(number) { // CSS Property; }

Q15. What's the difference between a relative, fixed, absolute and statically positioned element?

Ans. Relative Position: Setting the top, right, bottom, and left properties of an element with position: relative; property will cause it to adjust from its normal position. The other objects or elements will not fill the gap.

Syntax: position: relative;

Fixed Position: Position: fixed; property applied to an element will cause it to always stay in the same place even if the page is scrolled. To position the element we use top, right, bottom, left properties.

Syntax: position: fixed;

Absolute Position: An element with position: absolute; will cause it to adjust its position with respect to its parent. If no parent is present, then it uses the document body as parent.

Syntax: position: absolute;

Static positioning: Static positioning is the default that every element gets. It just means "put the element into its normal position in the document flow — nothing special to see here."

Syntax: position: absolute;

Q16. What existing CSS frameworks have you used locally, or in production? How would you change/improve them?

Ans.

Q17. Have you used CSS Grid?

Ans. Yes I used CSS Grid. The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.
