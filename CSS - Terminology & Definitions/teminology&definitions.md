1. What are the main differences between external, internal, and inline CSS?
- External CSS - the <link> element is placed inside the HEAD of the HTML file, and the CSS code is in a separate, CSS file
- Internal CSS - the <style> element is placed inside the head section of an HTML file, as well as the CSS code
- Inline CSS -  the <style> atribute and the CSS code is places inside an HTML element

2. What is the syntax for class and ID selectors?
 - It's dot (".") for class and hash character ("#") for id.

3. How would you apply a single rule to two different selectors?
- By listing the selectors with a comma between them.

4. Given an element that has an id of title and a class of primary, how would you use both
attributes for a single rule?
- #title, .class {}.

5. What does the descendant combinator do?
 - It combines two selectors such that elements matched by the second selector are selected if they have an ancestor
 (parent, parent's parent, parent's parent's parent, etc.) element matching the first selector. 
6. Between a rule that uses one class selector and a rule that uses three type selectors,
which rule has the higher specificity?
 - The class selector.

7. From inside to outside, what is the order of box-model properties?
 - Padding, Border, Margin.

8. What does the box-sizing CSS property do?
 - It sets how the total width and height of an element is calculated.

9. What is the difference between the standard and alternative box model?
- In the standard box model, the size of the border is added to the width and height of the content box, while in the alternative box model
the e size of the border makes the content box smaller as it takes up some of that available width and height of the element box.

10. Would you use margin or padding to create more space between 2 elements?
- Margin.

11. Would you use margin or padding to create more space between the contents of an
element and its border?
- Padding.

12. Would you use margin or padding if you wanted two elements to overlap each other?
- Margins, because padding can only pe positive.
 
13. What is the difference between a block element and an inline element?
- The block elements occupies the entire horizontal space of its parent element and vertical space equal to the height of its contents, while 
the inline elements will only occupy the space bounded by the tags defining the element.

14. What is the difference between an inline element and an inline-block element?
- On the inline element you can't set height and width values, while on the inline-block element you can.

15. Is an h1 block or inline?
- Block.

16. Is button block or inline?
- Inline.

17. Is div block or inline?
- Block.

18. Is span block or inline?
- Inline.

19. What’s the difference between a flex container and a flex item?
- The flex container is the parent, the flex item is the child. The element that has the display flex property is the parent.

20. How do you create a flex item?
- I would set the display flex property to its parent.

21. What are the 3 values defined in the shorthand flex property?
- Flex-grow, Flex-shrink and Flex-basis.
 
22. How do you make flex items arrange themselves vertically instead of horizontally?
- We set the property  flex-direction: row.

23. What is the difference between justify-content and align-items?
- Justify-content works across the main axis while align-items works on the cross-axis. 

24. How do you use flexbox to completely center a div inside a flex container?
- We use align-items: center and justify-content: center.

25. What’s the difference between justify-content: space-between and justify-content:
space-around?
- Space-between adds equal space just between the elements, while space-arounds adds equal space also before the first element and after the last element.