

## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
    Answer: getElementById returns only one element based on a specific ID but getElementsByClassName returns multiple elements based on the class name and querySelector returns only first matching element but querySelectorAll returns all(Node list) matching elements.

### 2. How do you create and insert a new element into the DOM?
    Answer: Using createElement and appendChild, we can create a new HTML element and insert it to the DOM.

### 3. What is Event Bubbling? And how does it work?
    Answer: Event bubbling is a mechanism in the DOM where, when an event is triggered on an element, it bubbles upward through the DOM tree from the child element to the parent elements.

### 4. What is Event Delegation in JavaScript? Why is it useful?
   Answer: Event Delegation is a mechanism where we can attach a single event listener to a parent element instead of adding separate listeners to multiple child elements.
   Event delegation is useful because of
   - it handles dynamic Elements Easily
   - it makes my code cleaner and faster
   - its improved performance.

### 5. What is the difference between preventDefault() and stopPropagation() methods?
    
