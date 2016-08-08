# Designkit Sets

## Install

```bash
npm i designkit-sets
```

## Usage

```html
<a href="#" class="set"><span class="set-label">Pens</span><span class="set-count">9</span></a>
```

## The CSS

```css
/*
//
// designkit-sets
// --------------------------------------------------
*/
.set {
  display: inline-block;
  margin-right: 6px;
  font-family: "Helvetica Neue", "Helvetica", "Roboto", "Arial", sans-serif;
  font-size: 12px;
  color: #fff;
  text-decoration: none;
  background: #76899A;
  border-radius: 2px;
  outline: none;
}

.set .set-label,
.set .set-count {
  padding: 3px 8px 3px 8px;
}

.set .set-label {
  float: left;
  border-radius: 2px 0 0 2px;
}

.set .set-count {
  float: right;
  background-color: rgba(0, 0, 0, 0.25);
  border-radius: 0 2px 2px 0;
}

.set:hover {
  background-color: #0A83F6;
}

.set.active, .set.active:hover {
  background-color: #80C11A;
}
```

## Author

Jason Melgoza

## License

The MIT License (MIT)

Copyright (c) 2016 RightScale

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
