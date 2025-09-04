1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll

getElementById finds one element by its id. getElementsByClassName finds many elements with the same class. querySelector finds the first match using CSS selectors, and querySelectorAll finds all matches.

2. How do you create and insert a new element into the DOM?

We use createElement to make a new element. Then we can add text or content to it. Finally, we use appendChild or similar methods to place it on the page.

3. What is Event Bubbling and how does it work?

Event bubbling means when an event happens on a child element, it also moves up to its parent, then to higher parents. For example, clicking a button also triggers events on its parent div.

4. What is Event Delegation in JavaScript? Why is it useful?

Event delegation means adding one event listener to a parent instead of many children. The parent checks which child was clicked. It is useful because it saves code and works for new children too.

5. What is the difference between preventDefault() and stopPropagation() methods?

preventDefault stops the normal action, like stopping a link from opening. stopPropagation stops the event from going up to parent elements.