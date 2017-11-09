---
title: Box Shadow
---
The box-shadow CSS property is used to add shadow effects around an element's frame. You can specify multiple effects separated by commas if you wish to do so. A box shadow is described by X and Y offsets relative to the element, blur and spread radii, and color.

/* offset-x | offset-y | color */
box-shadow: 60px -16px teal;

/* offset-x | offset-y | blur-radius | color */
box-shadow: 10px 5px 5px black;

/* offset-x | offset-y | blur-radius | spread-radius | color */
box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);

/* inset | offset-x | offset-y | color */
box-shadow: inset 5em 1em gold;

/* Any number of shadows, separated by commas */
box-shadow: 3px 3px red, -1em 0 0.4em olive;

/* Global keywords */
box-shadow: inherit;
box-shadow: initial;
box-shadow: unset;
box-shadow: 60px -16px teal;box-shadow: 10px 5px 5px black;box-shadow: 3px 3px red, -1em 0 0.4em olive;box-shadow: inset 5em 1em gold;box-shadow: 0 0 1em gold;box-shadow: inset 0 0 1em gold;box-shadow: inset 0 0 1em gold, 0 0 1em red;
 
The box-shadow property enables you to cast a drop shadow from the frame of almost any element. If a border-radius is specified on the element with a box shadow, the box shadow takes on the same rounded corners. The z-ordering of multiple box shadows is the same as multiple text shadows (the first specified shadow is on top).

Box-shadow generator is an interactive tool allowing you to generate a box-shadow.
```
It uses very similar code, but with inset value, which displays shadow inside div element

![image](https://raw.githubusercontent.com/krzysiekh/images/master/box-shadow2.png)
