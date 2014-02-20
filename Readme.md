*This repository is a mirror of the [component](http://component.io) module [component/ellipse](http://github.com/component/ellipse). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-ellipse`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# ellipse

  Generates an array of the coordinate points into the given area along ellipse

  You can see ellipse() in action in [this github page](http://component.github.com/ellipse/).

## Installation

```
$ component install component/ellipse
```

## API

## ellipse(width, height, points, options)

### options

  - `ini` initial angle in sexagesimal system (default: 0)
  - `end` end angle in sexagesimal system (default: 360)
  - `times`: times that the computing process will be executed (default: 100)
  - `arrangement`: "normal" | "inside" | "symmetric" (default: "normal")
  - `w`: point width (defaut: 0)
  - `h`: point height (defaut: 0)
  - `round`: rounding math function "ceil" | "floor" | "round" | false
  (default: false)

```js
var ellipse = require('ellipse');
var points = ellipse(400, 220, 19); // return the array of points
```

## Credits

  - mathematical computation by [Carly Stambaugh](https://github.com/stambizzle)  @stambeezi

## License

  (The MIT License)

  Copyright(c) 2012 Damian Suarez &lt;rdsuarez@gmail.com&gt;
  
  Permission is hereby granted, free of charge, to any person obtaining
  a copy of this software and associated documentation files (the
  'Software'), to deal in the Software without restriction, including
  without limitation the rights to use, copy, modify, merge, publish,
  distribute, sublicense, and/or sell copies of the Software, and to
  permit persons to whom the Software is furnished to do so, subject to
  the following conditions:
  
  The above copyright notice and this permission notice shall be
  included in all copies or substantial portions of the Software.
  
  THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
  EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
  MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
  IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
  CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
  TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
  SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
