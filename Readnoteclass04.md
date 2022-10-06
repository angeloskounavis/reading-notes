# Read: Class 04

## HTML

### To create a basic link, we wrap text or other content inside what element?

* We wrap the text around the anchor element and use the href attribute that contains the address.

### The href attribute contains what information?

* It contains the web address (find my source link at the end of the page)

### What are some ways we can ensure links on our pages are accessible to all readers?

* Hyperlinks can be used to make sure that our page is accessible to all readers.
* Also we should make sure that when we copy links we use the correct name and have no spelling mistakes.
* You can also use title to contain information about the link

## CSS

### What is meant by “normal flow”?

* Normal flow is when we haven’t really made any changes to the website yet. It’s the way the web browser is laid out by default.

### What are a few differences between block-level and inline elements?

* According to the article normal flow “block-level content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content.” While the size of the inline element is just the size of content (source is given at the end).

### ___ positioning is the default for every html element

* Static positioning

### Name a few advantages to using absolute positioning on an element

* According to the article Using Absolute Positioning in CSS some of the benefits are:
* “Aside from a few IE bugs, very good cross-browser support”
* “Less dependence on floats, which can be problematic”
* “Less dependence on margins, which can be a bit buggy in older IE” (link source is given below)

### What is a key difference between fixed positioning and absolute positioning?

* According to the article Positioning “Absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), fixed positioning usually fixes an element in place relative to the visible portion of the viewport.”

## JavaScript

### Describe the difference between a function declaration and a function invocation

* A function declaration, It is always hoisted, so you can call the function and it’s going to work. According to the article W3 Schools, “The code inside a function is not executed when the function is defined.The code inside a function is executed when the function is invoked”.

### What is the difference between a parameter and an argument?

* The difference is that certain functions need parameters in order to be invoked (values inside parentheses).While arguments usually send the values to the function, values are declared within the function.

### Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey

* Collaboration is important because it teaches both people new skills and they come up with a result that’s probably better than what they would have made by themselves in half the time.
Nowadays pair programming is used as a form of interviews so the sooner you get used to it the better. Personally, anytime I had to collaborate with someone I always had a good time and produced a much better result. I hope this time is no different.

### sources:

1. https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning#:~:text=This%20works%20in%20exactly%20the,relative%20to%20the%20visible%20portion


2. https://www.impressivewebs.com/absolute-position-css/#:~:text=Some%20of%20the%20benefits%20of,bit%20buggy%20in%20older%20IEWhat%20is%20a%20key%20difference%20between%20fixed%20positioning%20and%20absolute%20positioning?

3. https://www.w3schools.com/js/js_function_invocation.asp

4. https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning

5. https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks