# efec-flexible fork from amfe-flexible

[Classic edition (0.3.2)](https://github.com/ef-labs-ec/lib-flexible/tree/master)

## 3.0 New Feature

```html
<html maxWidth="600">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no">
<script src="./node_modules/efec-flexible/index.js"></script>
</html>
```

You can set maxWidth on html to define the max device width for compute rem,
the default value of it is `540`, which is found at [Device Table](https://material.io/devices/) 

## Usage

#### Install

`npm i -S efec-flexible`

#### Import

```html
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no">
<script src="./node_modules/efec-flexible/index.js"></script>
```

You can inline this file with [inline-source](https://npmjs.org/package/inline-source).

#### Develop

Use [postcss-adaptive](https://www.npmjs.com/package/postcss-adaptive).

## License

(The MIT License)

Copyright (c) 2016 EF-LABS-EC FE

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
