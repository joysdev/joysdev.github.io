Following about an hour of dead-end searches, I reverted to reviewing foundational CSS at [freecodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/#learn-basic-css-by-building-a-cafe-menu). By applying some of those steps, I was able to finally get my text to center on the page over my background, but the victory felt hollow because I'm not confident I did it the "right" way... This may be one reason for something I've been disappointed to notice lately-achieving my weekly goals rarely leaves me feeling any satisfaction. I make an effort to hype it up by writing journals with plenty of "Woohoo!"s and "Go me!!!"s, and barely any of it is sinking in; my heart is still anchored by grief and loneliness. 

I want to network (with humans), but between working my current job, looking for a new job, trying to move in order to reduce commutes, and programming study/practice, and fulfilling my basic needs for sleep, exercise, and healthy food, I have zero time. I'm painfully aware social connection is also a basic human need, but until something else in my life gets easier, I don't see how I'll meet it. Sigh.

In the mean time-I am rocking!! Yay! Go me... I did just look again at my code, and I think it is Good Enough. Judge me if you want:

```css
/* style.css */

body {
    background: 
    linear-gradient(red, transparent),
    linear-gradient(to top left, lime, transparent),
    linear-gradient(to top right, blue, transparent);
    background-blend-mode: screen;
    width: 100vh;
    height: 100vh;
    
}
h1, h2, p {
    margin: auto;
    text-align: center;
}
.testheading {
    width: 100%;
    margin-left: 50%;
    margin-right: auto;
}
```
![screenshot of centered text over gradient background](https://i.imgur.com/PJb8giz.png)