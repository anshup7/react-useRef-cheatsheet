# React useRef DOM Manipulation Cheat Sheet

## Table of Contents
1. Create Reference
2. Access Current Element
3. Add Class
4. Remove Class
5. Toggle Class
6. Check Class
7. Set Style
8. Get Style
9. Set Attribute
10. Get Attribute
11. Remove Attribute
12. Set Inner HTML
13. Get Inner HTML
14. Set Text Content
15. Get Text Content
16. Add Event Listener
17. Remove Event Listener
18. Focus Element
19. Blur Element
20. Scroll Into View
21. Set Value (for form elements)
22. Get Value (for form elements)

## Actions and Code Snippets

### 1. Create Reference
**Action:** Initialize a ref to be attached to a DOM element.
**Code Snippet:** `const dropContainer = useRef(null);`

### 2. Access Current Element
**Action:** Retrieve the current DOM element.
**Code Snippet:** `const element = dropContainer.current;`

### 3. Add Class
**Action:** Add a class to the element.
**Code Snippet:** `dropContainer.current.classList.add('your-class-name');`

### 4. Remove Class
**Action:** Remove a class from the element.
**Code Snippet:** `dropContainer.current.classList.remove('your-class-name');`

### 5. Toggle Class
**Action:** Toggle a class on the element.
**Code Snippet:** `dropContainer.current.classList.toggle('your-class-name');`

### 6. Check Class
**Action:** Check if the element has a specific class.
**Code Snippet:** `dropContainer.current.classList.contains('your-class-name');`

### 7. Set Style
**Action:** Set an inline style property.
**Code Snippet:** `dropContainer.current.style.color = 'red';`

### 8. Get Style
**Action:** Get an inline style property.
**Code Snippet:** `const color = dropContainer.current.style.color;`

### 9. Set Attribute
**Action:** Set an attribute on the element.
**Code Snippet:** `dropContainer.current.setAttribute('id', 'new-id');`

### 10. Get Attribute
**Action:** Get the value of an attribute from the element.
**Code Snippet:** `const id = dropContainer.current.getAttribute('id');`

### 11. Remove Attribute
**Action:** Remove an attribute from the element.
**Code Snippet:** `dropContainer.current.removeAttribute('id');`

### 12. Set Inner HTML
**Action:** Set the HTML content inside the element.
**Code Snippet:** `dropContainer.current.innerHTML = '<p>New Content</p>';`

### 13. Get Inner HTML
**Action:** Get the HTML content inside the element.
**Code Snippet:** `const html = dropContainer.current.innerHTML;`

### 14. Set Text Content
**Action:** Set the text content inside the element.
**Code Snippet:** `dropContainer.current.textContent = 'New Text';`

### 15. Get Text Content
**Action:** Get the text content inside the element.
**Code Snippet:** `const text = dropContainer.current.textContent;`

### 16. Add Event Listener
**Action:** Add an event listener to the element.
**Code Snippet:** `dropContainer.current.addEventListener('click', handleClick);`

### 17. Remove Event Listener
**Action:** Remove an event listener from the element.
**Code Snippet:** `dropContainer.current.removeEventListener('click', handleClick);`

### 18. Focus Element
**Action:** Set focus on the element.
**Code Snippet:** `dropContainer.current.focus();`

### 19. Blur Element
**Action:** Remove focus from the element.
**Code Snippet:** `dropContainer.current.blur();`

### 20. Scroll Into View
**Action:** Scroll the element into view.
**Code Snippet:** `dropContainer.current.scrollIntoView();`

### 21. Set Value (for form elements)
**Action:** Set the value of a form element (like an input or textarea).
**Code Snippet:** `dropContainer.current.value = 'new value';`

### 22. Get Value (for form elements)
**Action:** Get the value of a form element (like an input or textarea).
**Code Snippet:** `const value = dropContainer.current.value;`
