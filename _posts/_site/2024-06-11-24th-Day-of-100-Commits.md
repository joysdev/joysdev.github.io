### Solution to undesirable repeating gradient background

First, I tried background-repeat: no-repeat; and then I tried setting my body width and height to 100% and cover. These resulted in a single gradient, but only for the body, not the whole page. Finally, I searched for "how to make my body whole page" and found the solution at [Geeks for Geeks](https://www.geeksforgeeks.org/how-to-make-body-height-to-100-of-the-browser-height/).

```css
/* style.css */

body {
    background: radial-gradient(cyan, darkblue);
    width: 100vh;
    height: 100vh;
}
```
![screenshot of a full, single radiant gradient background](https://i.imgur.com/TUOI6cN.png)

And [this Stack Overflow post](https://stackoverflow.com/questions/34659486/change-the-flow-of-colours-in-a-css-gradient) is where I learned to play with adding percentages to my gradient colors to change where one fades into the other-I'm the kind of nerd who could mess around with this kind of thing, happily ever after... 