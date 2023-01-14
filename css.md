1. What is CSS and how does it work with HTML?
   -> Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML CSS describes how element should be rendered on screen, on paper, in speech, or on other media.

2. What are the selectors and what are their different types?
   -> Selectors used to find or select the HTML element you want to style.
   for example (CSS Element Selector (p), ID Selector (#para), Class Selector (.para))
   and the Universal Selector(\*)

3. What is CSS Selector specifically and how does it work?
   -> Specificity is an algorithm calculates the weight that is applied to a given CSS declaration.

4. Describe z-index and how stacking context is formed.
   -> The z-index property specifies the stack order of an element. An element with greater stack order is always in front of an element with a lower stack order.

5. Describe BFC (Block Formatting Context) and how it works.
   -> A block formatting context (BFC) is a part of visual CSS rendering of a web page. it's the region
   in which the layout of block boxes occurs and in which floats interact with other elements. the block formatting context is created usually by : The root element of the document

6. Have you ever used or implemented media queries or mobile specific layouts/CSS?
   -> Yes i have, mobile queries help you align and specifically set your positioning as your vertical phone wants, it allow you to apply CSS styles depending on a device's general type.

7. Have your ever used a grid system, and if so what do you prefer?
   -> Yes i have, used a grid system and i generally prefer Grid over Flex-FlexBox it's really optimizable  
   and helps you set your desired properties of grid accordingly.

8. Explain how a browser determines what elements match a CSS selector.
   -> Browsers match a selectors from rightmost (key selector) to left. Browsers filter out elements in the DOM according to the key selector and traverse up it's parent elements to determine matches.

9. Describe pseudo-elements and discuss what they are used for.
   -> A CSS pseudo-element is used to style specified parts of an element. for example, it can be used to:
   Style the first letter or line of an element or Insert content before or after the content of an element.

10. Explain your understandings of the box model.
    -> Everything in CSS had a box around it, and understandings these boxes is key being able to create more complex layouts with CSS, or to align items with other items. or to align items with other items.
    Every box has its own space.

11. What does \* {box-sizing:border-box} do? What are its advantages?
    -> The box-sizing property allows us to include the padding and border in an elements total Width and height.
    border-box tells the browser to account for any border and padding in the values you specify for an element's width and height.

12. What is the CSS display property and can you give a few example of its use?
    -> The display CSS property sets whether an element is treated as a block or inline. element and the layout
    used for its children, such as flow layout, grid or flex.

13. What's the difference between inline and inline-block?
    -> The display: inline-block Value, Compared to display: inline, the major difference is that display: inline-block allows to set a width and height on the element. Also, with display: inline-block, the top and bottom margins/paddings are respected, but with display: inline they are not.

14. What is the difference between the 'nth-of-type()' and 'nth-child()' selectors?
    -> nth-child() Selector is used to match the elements based on their position in a group of siblings, it matches every element that is the nth-child regardless of the type of its parent

    nth-of-type() Selector is used to style only those elements which are the nth number of children of its parent element. Any n may be a number, a keyword, or a formula.children

15. What's the difference between a relative, fixed, absolute and statically positioned element?
    -> in the Static the default value, all elements are in order as they appear in the DOM or document
    in the Relative the element is positioned relative to its normal position.
    in the Absolute the element is positioned absolutely to its first positioned parent.
    in the Fixed the element is positioned related to the browser window.
    in the Sticky the element is positioned based on the user's scroll position.

16. What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
    -> Bootstrap and Tailwind CSS these two i have used personally, as well as in production, tailwind and bootstrap are both really good and has flexible commands and functionality, bootstrap has pre applied css styling so you can attach it through class names and tailwind is really good with inline css writing
    when you have big project and wants to apply it directly.

17. Have you used CSS Grid?
    -> Yes i have, it's really helpful while aligning cards or products as grid or in similar sense.
    makes styling easier in general.
