# CSC313-First-Assignment-Template

Either manually, or using copilot, generate a simple HTML webpage that does the following:

Displays Hello World!

Displays a button that changes "World" to a name that you enter.

Key to this are two specific items:
1) The body, that is the main HTML, contains a level 1 header that has an ID. https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Global_attributes/id
2) The body will also contain a button with an onclick property that triggers a function that you provide.
3) The head of the page will contain a script block that contains the function you specified in onclick.
4) In the function, use "prompt" to get a new name, and then use the DOM editing: "document.getElementById("your id").textContent = "Hello " + name + "!"
