# CSS Text Manipulation

## Introduction
CSS (Cascading Style Sheets) provides various properties to manipulate text appearance and formatting. These properties help in improving readability, enhancing the design, and controlling how text elements are displayed on a webpage. Below is a detailed breakdown of key CSS text manipulation properties.

---

##  Color
### Definition:
The `color` property is used to set the color of text in an element. It accepts color values in different formats:
- Named Colors: `red`, `blue`, `green`
- HEX Codes: `#ff0000`, `#00ff00`, `#0000ff`
- RGB: `rgb(255, 0, 0)`
- RGBA: `rgba(255, 0, 0, 0.5)` (with opacity)
- HSL: `hsl(0, 100%, 50%)`

### Example:
```css
p {
  color: blue;
}
```

---

##  Direction
### Definition:
The `direction` property specifies the text direction.

### Values:
- `ltr` (Left-to-Right) - Default
- `rtl` (Right-to-Left) - Used for languages like Arabic and Hebrew

### Example:
```css
div {
  direction: rtl;
}
```

---

## Letter Spacing
### Definition:
The `letter-spacing` property adjusts the space between characters in text.

### Values:
- Normal: `letter-spacing: normal;` (default)
- Specific values: `letter-spacing: 2px;` or `letter-spacing: 0.2em;`

### Example:
```css
h1 {
  letter-spacing: 3px;
}
```

---

## Word Spacing
### Definition:
The `word-spacing` property controls the space between words in a text.

### Example:
```css
p {
  word-spacing: 5px;
}
```

---

##  Text Indent
### Definition:
The `text-indent` property sets the indentation of the first line of a text block.

### Example:
```css
p {
  text-indent: 50px;
}
```

---

##  Text Align
### Definition:
The `text-align` property controls the alignment of text inside an element.

### Values:
- `left` (default)
- `right`
- `center`
- `justify` (aligns text to both left and right margins)

### Example:
```css
div {
  text-align: center;
}
```

---

##  Text Decoration
### Definition:
The `text-decoration` property adds decorative lines to text.

### Values:
- `none` (default)
- `underline`
- `overline`
- `line-through`
- `blink` (not widely supported)

### Example:
```css
a {
  text-decoration: underline;
}
```

---

##  Text Transform
### Definition:
The `text-transform` property modifies the capitalization of text.

### Values:
- `none` (default)
- `uppercase`
- `lowercase`
- `capitalize`

### Example:
```css
h2 {
  text-transform: uppercase;
}
```

---

##  White Space
### Definition:
The `white-space` property determines how white spaces are handled within an element.

### Values:
- `normal` (default)
- `nowrap` (prevents text wrapping)
- `pre` (preserves spaces and line breaks)
- `pre-wrap` (preserves spaces but allows wrapping)
- `pre-line` (collapses spaces but preserves line breaks)

### Example:
```css
div {
  white-space: nowrap;
}
```

---

##  Text Shadow
### Definition:
The `text-shadow` property applies shadow effects to text.

### Syntax:
```css
text-shadow: h-offset v-offset blur-radius color;
```

### Example:
```css
h1 {
  text-shadow: 2px 2px 5px gray;
}
```

---

## Conclusion
These CSS properties provide extensive control over text styling and formatting, improving both aesthetics and readability in web design. Mastering these properties helps in creating visually appealing and accessible webpages.

