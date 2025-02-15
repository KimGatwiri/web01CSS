

# CSS - Applying Colors

## 1. Color Values in Various Formats
CSS allows you to define colors using multiple formats, including:
- Named Colors (e.g., `red`, `blue`, `green`)
- Hexadecimal Codes (e.g., `#ff0000` for red)
- Short Hex Code (e.g., `#f00` for red)
- RGB Values (e.g., `rgb(255, 0, 0)` for red)
- RGBA (RGB with Alpha for transparency, e.g., `rgba(255, 0, 0, 0.5)`)
- HSL (Hue, Saturation, Lightness, e.g., `hsl(0, 100%, 50%)` for red)
- HSLA (HSL with Alpha, e.g., `hsla(0, 100%, 50%, 0.5)`)

## 2. Color-Name Keywords
CSS provides over 140 predefined color names that can be used directly. Examples include:
```css
color: red;
color: blue;
color: green;
background-color: yellow;
```
These named colors are easy to remember and commonly used in simple designs.

## 3. Hexadecimal Color Codes
Hex codes are a widely used format for defining colors in CSS. A hex code consists of a `#` followed by six characters representing red, green, and blue values:
```css
color: #ff5733; /* Orange */
color: #3498db; /* Blue */
background-color: #2ecc71; /* Green */
```
Each pair of characters represents intensity (00 to FF) of red, green, and blue.

## 4. Short Hex Code
A shorthand version of the hex code can be used when each pair has identical values. Instead of six characters, you use three:
```css
color: #f00; /* Red (#ff0000) */
color: #0f0; /* Green (#00ff00) */
color: #00f; /* Blue (#0000ff) */
```
This reduces file size and makes the CSS more compact.

## 5. RGB and RGB%
RGB (Red, Green, Blue) values allow defining colors using numeric values between `0-255` or percentages.
```css
color: rgb(255, 0, 0); /* Red */
color: rgb(0, 128, 0); /* Green */
color: rgb(0, 0, 255); /* Blue */
```
You can also use percentages:
```css
color: rgb(100%, 0%, 0%); /* Red */
color: rgb(0%, 50%, 0%); /* Dark Green */
color: rgb(0%, 0%, 100%); /* Blue */
```

## 6. CSS Text Color and Background Color Implementations

### Text Color
To set the text color of an element, use the `color` property:
```css
p {
    color: blue;
}
h1 {
    color: #ff6600;
}
```

### Background Color
To set the background color of an element, use `background-color`:
```css
div {
    background-color: lightgray;
}
body {
    background-color: #f4f4f4;
}
```

### Example of Applying Colors in a Web Page
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Colors</title>
    <style>
        body {
            background-color: #f0f0f0;
            color: #333;
        }
        h1 {
            color: #ff5733;
        }
        p {
            color: rgb(0, 128, 255);
        }
        .highlight {
            background-color: yellow;
            color: black;
        }
    </style>
</head>
<body>
    <h1>CSS Color Implementation</h1>
    <p>This is an example of text with an <span class="highlight">inline colored background</span>.</p>
</body>
</html>
```

This example demonstrates text colors, background colors, and various color formats in action.
