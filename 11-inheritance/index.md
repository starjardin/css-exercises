# CSS exercise 11: Inheritance

Let's do some research on what we commonly refer to as *inheritance* in CSS.

Try to answer the following questions:

- What do we mean by *CSS inheritance*? What does it affect?
- Which properties have values that are inherited by default?
- What is the difference between the `currentColor` and `inherit` keywords when used with colour values?
- What do the `revert`, `initial`, and `unset` keyword values do?
- Are there any dangers or unintended side-effects when using `inherit` as a value? What about the `revert`, `initial` and `unset` properties?
- What are the possibilities with using an ancestor or universal selector, combined with the `inherit` value?

- Answers

- When we use *CSS inheritance*, we mean to inherit the parent's value to its children. That means the children will have the same value as their parents if we don't specify their value.

- It affects the curent values to its descendent.

- Here are some exemple of properties have values that are inherited by default: color, font, font-family, font-size, font-style, font-variant, font-weight, letter-spacing, line-height, text-align, text-indent, text-transform, visibility.

- Using revert , you will put back those styles while unset will not.
 unset will simply set the margin to initial,
 The 'initial' keyword represents the specified value that is designated as the property's initial value. Thus, its meaning depends on the property, but not on anything else.

 -Tehre might be some dangers or unintended side-effects when using `inherit` as value if you dont want the children to have the value as its parents.

The possibilities with using an ancestor or universal selector are 
