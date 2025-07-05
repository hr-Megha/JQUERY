Your browser will run any JavaScript inside a script element, including jQuery.
All jQuery functions start with a $, usually referred to as a dollar sign operator, or as bling.
jQuery often selects an HTML element with a selector, then does something to that element.
Now you know three ways of targeting elements: by type: $("button"), by class: $(".btn"), and by id $("#target1").
Although it is possible to add multiple classes in a single .addClass() call, let's add them to the same element in three separate ways.
In the same way you can add classes to an element with jQuery's addClass() function, you can remove them with jQuery's removeClass() function.
We can also change the CSS of an HTML element directly with jQuery.
jQuery has a function called .css() that allows you to change the CSS of an element.
You can also change the non-CSS properties of HTML elements with jQuery. For example, you can disable buttons.

When you disable a button, it will become grayed-out and can no longer be clicked.

jQuery has a function called .prop() that allows you to adjust the properties of elements.
Using jQuery, you can change the text between the start and end tags of an element. You can even change HTML markup.
jQuery has a function called .html() that lets you add HTML tags and text within an element. Any content previously within the element will be completely replaced with the content you provide using this function.