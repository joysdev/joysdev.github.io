### Problem: undesirable repeating gradient  
This is my page background:  

![screenshot of webpage whose background is 3 gradients](https://i.imgur.com/docZd4G.png)  
 with the following code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Odin Recipe Project</title>
</head>
<body>
    <h1>Odin Recipes</h1>
    <a href="recipes/fettucinecaprese.html">Fettucine Caprese</a><p></p>
    <a target="_blank" class="bp-btn" href="recipes/blueberriedpancakes.html">Externally-styled Blueberried Pancakes</a>
    </body>
</html>
```
```css
/* style.css */

   body {
    background: radial-gradient(cyan, darkblue);
}
.bp-btn {
    background-color: blue;
    color: white;
    padding: 15px 25px;
    text-decoration: none;
    }

h2.recipename {
    color: darkgreen;
}
```
And this  

![screenshot of a webpage whose background is many repeating gradients](https://i.imgur.com/0dZkDBd.png)
is what I get with this code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="mystyle.css">
</head>
<body>
</style> 
</body>
</html>
```
```css
/* style.css */

body {
    background: radial-gradient(cyan, darkblue);
}
```
Tomorrow I will start figuring out how to get a single gradient background. Tonight, I learned how to embed code in Markdown, and practiced embedding images with [The Goblin's Help](https://help.the-goblin.net/2021/12/01/hosting-images-on-imgur-com/). I'm building a better habit of ending my study/practice sessions on a high note at a healthy bedtime, and with a puzzle I look forward to learning more about tomorrow! 