# CanvasAnimater.js

CanvasAnimater.js is a utility script for animating, recording, and interacting with graphics using the [HTML5 canvas](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas). It is light weight, uses vanilla javascript, and has no dependencies.

At its core CanvasAnimater.js provides controlled frame-throttling to render an animation at a user specified frame rate, but its essence offers a way parametrize dynamic animations by exposing a relative time evolution variable.

Although this tool was developed for recreational creative coding purposes, its main functionality lends itself to any situation where rapid prototyping of Canvas animations is desired. Unlike other popular frameworks that achieve something similar, like [p5.js](https://p5js.org/), CanvasAnimater.js does not offer special drawing context primitives for rendering graphics beyond the native [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API). Seemingly more cumbersome, working directly with the Canvas API allows deeper control for generating graphics, and in this way CanvasAnimater.js gives us the best of both.

CanvasAnimater.js provides an intuitive interface with declarative style control of settings and the option of more refined functionality. Check out the interactive [guide]() for basic usage and consult the [API reference]() for details on all available settings and methods.