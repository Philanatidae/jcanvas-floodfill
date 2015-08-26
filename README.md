jcanvas-floodfill
=================

jcanvas-floodfill is a jCanvas plugin that allows for a flood fill on a canvas.
(jCanvas)[http://projects.calebevans.me/jcanvas/] is a plugin for jQuery by Caleb Evans to allow for canvas manipulation in jQuery form.
This plugin uses a script by Markus Ritberger called Flood Fill. Flood fill defines a function that flood fills a canvas. It is licensed under the MIT Open Source license.

Hot To Use
==========
Load the jcanvas-floodfill.js script after jCanvas. Use the drawFloodFill function to flood fill:

```javascript
$("#canvas").drawFloodFill({
	x: 0,
	y: 0,
	fromCenter: true,
	tolerance: 0,
	color: "#000000"
});
```

All of the properties are optional.

|Property   | Default | Function                                                                                                                         |
|--------   | ------- | --------                                                                                                                         |
|x          | 0       | X position of the flood fill                                                                                                     |
|y          | 0       | Y position of the flood fill                                                                                                     |
|fromCenter | true    | true if the origin is in the center of the canvas                                                                                |
|tolerance  | 0       | Tolerance level of flood fill for flooding gradients                                                                             |
|color      | #000000 | Color of flood fill (in hex, rgb(), rgba(), rgb array, or rgba array, however the Alpha channel is not supported and is stripped |

License
=======

jcanvas-floodfill - a canvasflood fill implementation by Markus Ritberger as
a plugin for jCanvas
 
Author: Philip Rader
Version: 1.1.0 (2015-08-26)
 
licensed under MIT license:
 
Copyright (c) 2015 Philip Rader

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to 
deal in the Software without restriction, including without limitation the 
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or 
sell copies of the Software, and to permit persons to whom the Software is 
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in 
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN 
THE SOFTWARE.
