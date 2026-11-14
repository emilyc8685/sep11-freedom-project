# Entry 1
##### 11/9/26

## Content
For my SEP11 freedom project i've been tinkering with different tools for a few weeks. I decided to choose [Kaboom](https://kaboomjs.com/) because Kaboom has many built in features that makes it easier to create a game. My idea for my SEP11 freedom project is to create a jump and running game where the player has to collect keys and avoid obstacles to move onto the next level. In order to collect the key the player must solve a math problem to get the key. I've been tinkering with Kaboom by following YouTube videos: [Easy Kaboom Game Developement]( https://m.youtube.com/watch?v=4OaHB0JbJDI&start=106) and the [Kaboom website](https://kaboomjs.com/). Some things I learned was how to create a map and make my character move. Here is some examples:

This is how I made my sprite move left or right: 
``` js
onKeyDown("left", () => {
    player.move(-SPEED, 0);
})

onKeyDown("right", () => {
    player.move(SPEED, 0);
})
```


This is how I made my sprite jump: 
```js
onKeyPress("space", () => {
    player.jump()
})
```
## Sources 
I've been tinkering with Kaboom by following YouTube videos: [Easy Kaboom Game Developement]( https://m.youtube.com/watch?v=4OaHB0JbJDI&start=106) and the [Kaboom website](https://kaboomjs.com/). Although another tool I considered was [Phaser](https://phaser.io/) because its great for beginners and an HTML5 game framework that helps users create games quickly.

## EDP
The step i'm currently at is planning my project. The next step is creating a prototype. 

## Skills 
* Debugging: There were many moments where I had to debug my code since my code didn't turn out how it was supposed to and by using the people around me and the sources I had I was able to fix some errors I had.
* Time management: I got better at managing my time with each learning log. 

[Next](entry02.md)

[Home](../README.md)
