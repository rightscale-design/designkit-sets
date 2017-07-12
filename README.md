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

MIT
