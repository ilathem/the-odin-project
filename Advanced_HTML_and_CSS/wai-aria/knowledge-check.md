# WAI-ARIA

1. What purpose does WAI-ARIA serve?

To make web content more accessible than html alone.

2. What are the four things ARIA can’t do?

Modify an element's appearance, behavior, add focusability, or keyboard
event handling.

3. What are the five rules of ARIA?

Use native html over aria when possible, change semantics
as a last resort, ARIA controls must be keyboard friendly,
never use `role = presentation` or `aria-hidden = true` on
focusable elements, and all interactive elements must have an accessible name.

4. What is the accessibility tree?

Similar to the DOM tree, but for assistive technologies.

5. What are the differences between the three ARIA labels?

`aria-label` modifies the element's name in the accessiblity tree,
`aria-labelledby` does the same as `aria-label`, and overrides the
native label, `aria-describedby` modifies the description part of the
accessibility tree.

6. What does the `aria-hidden` attribute do?

Hides an element from the accessiblity tree.
