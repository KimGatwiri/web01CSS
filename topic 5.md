# Applying CSS Fonts

## 1. Font Family Property
The `font-family` property specifies the typeface of the text.

```css
body {
    font-family: Arial, sans-serif;
}
```

## 2. Font Style Property
The `font-style` property specifies the style of the font.

```css
p {
    font-style: italic; /* Options: normal, italic, oblique */
}
```

## 3. Font Variant Property
The `font-variant` property specifies whether the text should be displayed in a small-caps font.

```css
h1 {
    font-variant: small-caps; /* Options: normal, small-caps */
}
```

## 4. Font Weight Property
The `font-weight` property sets how bold the text should be.

```css
strong {
    font-weight: bold; /* Options: normal, bold, bolder, lighter, or numeric values (100-900) */
}
```

## 5. Font Size Property
The `font-size` property controls the size of the font.

```css
p {
    font-size: 16px; /* Options: px, em, rem, %, etc. */
}
```

## 6. Font Property (Shorthand)
The `font` shorthand property allows setting multiple font-related properties in a single declaration.

```css
body {
    font: italic small-caps bold 16px/1.5 Arial, sans-serif;
}
