# CSS - Control Image Display

CSS provides powerful properties to control the appearance and behavior of images on a webpage. This guide covers essential properties such as `border`, `height`, `width`, and `moz-opacity`.

## 1. Border
The `border` property allows you to add a border around an image. You can specify the border style, width, and color.

### Syntax:
```css
img {
  border: 5px solid black;
}
```

### Explanation:
- `5px` → Sets the width of the border.
- `solid` → Specifies a solid border (other styles include `dotted`, `dashed`, `double`, etc.).
- `black` → Sets the color of the border.

### Example:
```html
<img src="image.jpg" style="border: 3px dashed red;" />
```

## 2. Height
The `height` property controls the vertical size of an image.

### Syntax:
```css
img {
  height: 200px;
}
```

### Explanation:
- `200px` → Defines the image height in pixels.
- Can also use percentages (`50%`), `auto` (keeps aspect ratio), or viewport units (`vh`).

### Example:
```html
<img src="image.jpg" style="height: 50%;" />
```

## 3. Width
The `width` property sets the horizontal size of an image.

### Syntax:
```css
img {
  width: 300px;
}
```

### Explanation:
- `300px` → Defines the image width in pixels.
- Can use relative units like `%`, `auto`, or viewport units (`vw`).

### Example:
```html
<img src="image.jpg" style="width: 100%;" />
```

## 4. Moz-Opacity
The `moz-opacity` property (specific to older Mozilla-based browsers) controls the transparency of an image. This property is now obsolete, but `opacity` is its modern alternative.

### Syntax:
```css
img {
  -moz-opacity: 0.5;
}
```

### Explanation:
- `0.5` → Sets image opacity (1 = fully visible, 0 = fully transparent).

### Modern Alternative:
```css
img {
  opacity: 0.5;
}
```

### Example:
```html
<img src="image.jpg" style="opacity: 0.7;" />
```

---

## Summary
| Property        | Description                                | Example |
|---------------|--------------------------------|---------|
| `border` | Adds a border around the image | `border: 2px solid blue;` |
| `height` | Sets the image height | `height: 200px;` |
| `width` | Sets the image width | `width: 300px;` |
| `moz-opacity` | Controls image transparency (deprecated) | `-moz-opacity: 0.5;` |
| `opacity` | Modern alternative to `moz-opacity` | `opacity: 0.5;` |

Use these properties to effectively style and control image display in your web projects! 🎨
