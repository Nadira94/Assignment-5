.

### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

Answer: In JavaScript, getElementById() selects a single element by its unique ID. getElementsByClassName() selects all elements with the same class name and returns them as a collection. querySelector() selects the first element that matches a CSS selector, while querySelectorAll() selects all elements that match a CSS selector and returns them as a list.

2. How do you **create and insert a new element into the DOM**?
Answer: We can create a new element using document.createElement() and then insert it into the page using appendChild() or append(). For example, creating a paragraph and adding it to the body will show the new element on the webpage.

3. What is **Event Bubbling** and how does it work?
Answer: Event bubbling is a way events work in JavaScript where an event starts from the target element and then moves upward through its parent elements in the DOM tree.

4. What is **Event Delegation** in JavaScript? Why is it useful?
Answer: Event delegation is when we put one event listener on a parent element instead of adding it to many child elements. It works because events bubble up from children to the parent. It is useful because it saves memory, makes code easier, and works for new elements added later.

5. What is the difference between **preventDefault() and stopPropagation()** methods?
Answer: preventDefault() stops the browser’s normal action, like opening a link or submitting a form.
stopPropagation() stops the event from moving up to parent elements.
