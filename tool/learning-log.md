# Tool Learning Log

## Tool: **Kaboom**

## Project: **Platform Game**

---

## Learning Log 1 
### 10/23/26:
* Setup Kaboom with their website: [Kaboom - Setup](https://kaboomjs.com/doc/setup) 
* I tinkered with Kaboom by watching this video: []()
   * After watching 15 minutes of the video I learned the basics of kaboom.js:
   * Draw a map with quotation marks, create a ground with `x` and define it.
   * `body()` adds gravity, `solid() stops sprite from falling`
   * Movement: `onKeyDown('right')` --> makes the sprite move with the right key on the keyboard
     * `player.move(100,0)` --> only makes the sprite move left or right (x-axis)
   * Collision: `destroy()` makes the sprite disappear


## Learning Log 2
### 11/5/26:
* I tinkered with Kaboom by adding a sprite and movement.
  * `setGravity()` adds gravity
  * `body({ isStatic: true })`: makes sure my sprite doesnt fall through the ground
  * `const player = add([ sprite("bean"),])` : adds the bean sprite
  * This is how I made my sprite jump: 
```js
onKeyPress("space", () => {
    player.jump()
})
```
  * This is how I made my sprite move left or right: 
``` js
onKeyDown("left", () => {
    player.move(-SPEED, 0);
})

onKeyDown("right", () => {
    player.move(SPEED, 0);
})
```





<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
