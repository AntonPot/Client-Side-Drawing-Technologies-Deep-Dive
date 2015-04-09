# client-side-drawing-thunder-talk

DBC deep dive into client side drawing technologies

Topics:
- HTML5 Canvas
- two.js
- D3.js
- C3.js
- Konva.js

Team: 
- Marko Anton Potocnik
- Erin Hyejin Kim
- Matt Lao
- Bao Tran


C3
----



Konva JS
----
Javascript library for drawing shapes and rendering images. Has a robust library that allows you to assign event listeners and actions to them, like dragging, scaling. High performance allows for many animations to be rendered at once. 

Could be a great use for games. 

You render all objects onto a "layer" of the "stage." 

Architecture: 

```
              Stage
                |
         +------+------+
         |             |
       Layer         Layer
         |             |
   +-----+-----+     Shape
   |           |
 Group       Group
   |           |
   +       +---+---+
   |       |       |
Shape   Group    Shape
           |
           +
           |
         Shape
```




