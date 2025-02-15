# Setting Backgrounds in HTML

## 1. Color Property
The `background-color` property sets the background color of an element.

```css
body {
    background-color: lightblue;
}
```

## 2. Image Property
The `background-image` property sets an image as the background.

```css
body {
    background-image: url('background.jpg');
}
```

## 3. Repeat Property
The `background-repeat` property defines how the background image is repeated.

```css
body {
    background-image: url('background.jpg');
    background-repeat: no-repeat; /* Options: repeat, repeat-x, repeat-y, no-repeat */
}
```

## 4. Position Property
The `background-position` property sets the starting position of a background image.

```css
body {
    background-image: url('background.jpg');
    background-position: center top; /* Example positions: left top, right bottom */
}
```

## 5. Attachment Property
The `background-attachment` property determines if the background image scrolls with the page.

```css
body {
    background-image: url('background.jpg');
    background-attachment: fixed; /* Options: fixed, scroll, local */
}
```

## 6. Background Property
The `background` shorthand property allows setting multiple background properties in one line.

```css
body {
    background: url('background.jpg') no-repeat center top fixed;
    background-size: cover;
}
