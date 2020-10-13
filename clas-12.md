# Code 201 Day 12 Reading Notes: Chart.js, Canvas

## Chart.js API

- Chart.js - a JavaScript plugin that uses canvas element in HTML5 to draw the graph on the page.
- can be used to make bar charts, line charts, pie charts, and more
- charts can be animated
- they are simple to use and flexible

## Chart.js docs

- is now bookmarked will be using this for reference going forward.

## Canvas API

`<canvas>` - 

- looks like the `<img>` element but doesn't include the `src` and `alt` attributes. 

- Only has `<width>` and `<height>` but they are option and can be set using DOM.

- default is 300px wide and 150px high

- CSS can be used to size it but aspect ratio needs to be the same.
- can add some fallback content if browser doesn't support it just add content inside the element
- make sure to add (`</canvas>`) tag otherwise rest of the text on the page might be missing if browswer supports canvas and ignores the text.

- use `getContext()` to obtain the rendering context
- `canvas.getContext('2d));`

- drawing shapes - canvas can be used to draw rectangles, triangles, lines, arcs, and curves.
- canvas grid or coordinate space. origin is top left (0,0) normally 1 unit = 1 px
- start with naming coordinated then add dims ex. `clearRect(x,y,width,height)`
-canvas can be used to 'draw' images on the page `beginPath()`, `closePath()`, `stroke()` and `fill()` 
- `moveTo(x,y)` is used to pick up the pen and move it to another location.

- colors and styles can be added to canvas as well
- `fillStyle` to fill shapes
- `strokeStyle` to add color
- `globalAlpha = transparencyValue` can be added to make a canvas element transparent of opaque.

- `fillText(text, x, y [ , maxwidth])`fills text
- `strokeText(text, x, yx[ , maxWidth])` strokes a given text at the guven (x,y) position.


[<-- Back](README.md)