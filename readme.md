# LesserPanda Text Extension (DEPRECATED)

TextPlus is a wrapper of [pixi-cocoontext](https://github.com/JiDW/pixi-cocoontext), which
provide an optimized Text class for PIXI.js.

## Usage

The `game.Text` is replaced, if you still want to use the old one, try `game.PIXI.Text`.

```javascript
// Create a text with "resolution" set to "game.scale" for better
// retina display
new game.Text('We who wander this wasteland in search of our better selves?', {
  font: '40px Roboto',
  fill: 'white'
}, game.scale).addTo(container);
```

## ChangeLog

### 0.1.0

- Simple wrap without any modification

## License

Original author of [pixi-cocoontext](https://github.com/JiDW/pixi-cocoontext): [Celsius online (@JiDW)](https://github.com/JiDW)

The MIT License (MIT)

Copyright (c) 2015 Sean Bohan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
