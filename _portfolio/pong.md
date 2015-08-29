---
layout: post
title: Pong
feature-img: "img/ponghead.png"
thumbnail-path: "img/pongthumb.png"
short-description: A remake of Pong

---

## Description

A remake of the classical game Pong.

![Pong]({{ site.baseurl }}/img/pong02.png)
![Pong]({{ site.baseurl }}/img/pong03.png)

A live demo is available on Heroku: [Pong](http://my-little-pong-game.herokuapp.com).  
The source code is available on Github: [Pong](https://github.com/amizony/pong).


## Context

For the third application I made, I wanted to 'go back to the basics', and make an application with as few helpers, libraries or frameworks as possible.
The idea behind it, was to learn how things really works, and be able to understand them and make them myself.
So I used only HTML, css and javascript. And for this exercise, I choose to do a classical game: Pong.

Beyond making the application working, the first objective was to produce the cleanest code as possible. Then the second one was to make a game that is actually fun to play.


## Features

Because there are already thousands of remakes for this game, on top of the basic game, I added some specials features to make it more personal:

* New graphics
* Two players mode
* Several AI difficulty level
* Ball speed calculated vectorially
* Paddle's movement influencing the bounce


Using a vectorial ball speed was a way to avoid the brutal speed change of the ball when the bouncing angle is changed (like in the original game).
Although it was adding challenge (and thus fun to the game), it had nothing to do with *real physics*.
So when changing this and using a real bouncing angle, the game lost all it's interest.
To counter it, I introduced the possibility to add an effect on the ball with the paddle's movements, influencing the bouncing angle and the ball speed.
