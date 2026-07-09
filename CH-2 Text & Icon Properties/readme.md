# Text & Icon Properties in CSS

A simple guide to the most commonly used **CSS Text** and **Icon** properties. This document is useful for beginners and front-end developers who want a quick reference for styling text and icons.

---

# Table of Contents

- Introduction
- Text Properties
- Icon Properties
- Best Practices
- Browser Support
- Resources

---

# Introduction

CSS provides a variety of properties to control the appearance of text and icons. Proper styling improves readability, accessibility, and the overall user experience.

---

# Text Properties

## 1. color

Changes the text color.

```css
h1 {
  color: #2563eb;
}
```

---

## 2. font-size

Sets the size of the text.

```css
p {
  font-size: 18px;
}
```

---

## 3. font-family

Defines the font used for the text.

```css
body {
  font-family: Arial, Helvetica, sans-serif;
}
```

---

## 4. font-weight

Controls the thickness of the text.

```css
h2 {
  font-weight: bold;
}
```

Common values:

- normal
- bold
- 100–900

---

## 5. font-style

Applies italic styling.

```css
em {
  font-style: italic;
}
```

---

## 6. text-align

Aligns text horizontally.

```css
h1 {
  text-align: center;
}
```

Values:

- left
- center
- right
- justify

---

## 7. text-decoration

Adds or removes text decorations.

```css
a {
  text-decoration: none;
}
```

Common values:

- none
- underline
- overline
- line-through

---

## 8. text-transform

Changes letter casing.

```css
h3 {
  text-transform: uppercase;
}
```

Values:

- uppercase
- lowercase
- capitalize

---

## 9. letter-spacing

Controls the space between letters.

```css
h1 {
  letter-spacing: 2px;
}
```

---

## 10. word-spacing

Controls spacing between words.

```css
p {
  word-spacing: 5px;
}
```

---

## 11. line-height

Controls the height of each text line.

```css
p {
  line-height: 1.8;
}
```

---

## 12. text-indent

Indents the first line of text.

```css
p {
  text-indent: 40px;
}
```

---

## 13. text-shadow

Adds shadow effects to text.

```css
h1 {
  text-shadow: 2px 2px 5px gray;
}
```

---

## 14. white-space

Controls how whitespace is handled.

```css
pre {
  white-space: pre-wrap;
}
```

---

## 15. overflow-wrap

Breaks long words when necessary.

```css
p {
  overflow-wrap: break-word;
}
```

---

# Icon Properties

Icons are commonly used with libraries like **Font Awesome**, **Bootstrap Icons**, and **Material Icons**.

Example:

```html
<i class="fa-solid fa-heart"></i>
```

---

## 1. color

Changes the icon color.

```css
i {
  color: red;
}
```

---

## 2. font-size

Changes icon size.

```css
i {
  font-size: 30px;
}
```

---

## 3. margin

Adds space around the icon.

```css
i {
  margin-right: 10px;
}
```

---

## 4. padding

Adds internal spacing.

```css
i {
  padding: 10px;
}
```

---

## 5. background-color

Adds a background behind the icon.

```css
i {
  background-color: #f3f4f6;
}
```

---

## 6. border-radius

Creates rounded or circular icons.

```css
i {
  border-radius: 50%;
}
```

---

## 7. transition

Adds smooth hover animations.

```css
i {
  transition: all 0.3s ease;
}
```

---

## 8. transform

Applies scaling or rotation.

```css
i:hover {
  transform: scale(1.2);
}
```

---

## 9. cursor

Changes the mouse cursor.

```css
i {
  cursor: pointer;
}
```

---

## 10. opacity

Adjusts icon transparency.

```css
i {
  opacity: 0.8;
}
```

---

# Example

## HTML

```html
<h1>Welcome</h1>

<p>
  Learn CSS text and icon styling.
</p>

<i class="fa-solid fa-heart"></i>
```

## CSS

```css
h1 {
  color: royalblue;
  text-align: center;
  text-transform: uppercase;
}

p {
  font-size: 18px;
  line-height: 1.7;
}

i {
  color: crimson;
  font-size: 30px;
  transition: 0.3s;
  cursor: pointer;
}

i:hover {
  transform: scale(1.2);
}
```

---

# Best Practices

* Use readable font sizes.
    - Hello
- Maintain sufficient color contrast for accessibility.
- Avoid excessive text shadows.
- Keep line-height between **1.4** and **1.8** for better readability.
- Use hover effects sparingly.
- Use SVG icons when possible for better scalability.

---

# Browser Support

All properties used in this guide are supported by modern browsers:

- Chrome
- Firefox
- Edge
- Safari
- Opera

---

# Resources

- MDN CSS Documentation
- CSS Tricks
- Font Awesome
- Bootstrap Icons
- Google Material Icons

---

# License

This project is available for learning and educational purposes.

---
![alt text](images/insta.jpg)
<br>
<br>
<br>
<br>
**Happy Coding! 🚀**