Still working on how to add onclick removal of a pose in customnewseq.

Wondering if display = "none" is a way. And/or an if function, like if > 1 field, onclick = display = "none", but wait would that remove all fields?

Experiencing my local test file sometimes working, sometimes not and it's unclear to me why it works when it works and why not when it doesn't-I set it up bare-bones, in order to be easy to spot, but I know I probably have plenty of blindspots, especially in JavaScript.

(Remove function method)[https://www.geeksforgeeks.org/how-to-remove-an-html-element-using-javascript/] which after experimenting, I don't think is the right one for me-I even tried changing it to class, instead of ID, but no dice. I can't fully explain it, but I'm not shocked it doesn't work.

(Display= "none" method)[https://www.geeksforgeeks.org/hide-or-show-elements-in-html-using-display-property/] is my next experiment. I predict it won't work because it will either hide all or I will have the same issue with naming. I may need a loop?? Can I even do an onclick that runs an if? It did not do what I wanted, but it is possible I made syntax mistakes. I did, but even when I fixed that, it still does not work, still not surprised. 

Theres the remove method, but (JavaScript.info)[https://javascript.info/] uses a timeout in their example, and that's not appropriate for my app.

I searched "javascript button to remove an input" and found (this shecodes.io)[https://www.shecodes.io/athena/46767-how-to-remove-html-added-with-javascript-on-button-click#:~:text=querySelector('%23myButton')%3B,remove()%3B%20%7D)%3B], which appears promising, in part because the original question puts my search in even more specific terms: "how do i remove html when i click a button that was originally added with js?" 

Diversion: I just had the idea to simply reverse my add-a-field function. It works, kinda-it will remove all fields and print NaN. This leads me to believe what I need is a function which executess only if there's more than one input field, then only removes the last one. 