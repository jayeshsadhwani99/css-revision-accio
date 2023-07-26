# CSS Revision

In this session, we'll revise the fundamentals of CSS, understand how to use different properties, and see how we can create more responsive designs.

## Part-1: CSS Basics

- **CSS syntax and selectors**
  - Selectors: names of HTML tags used to apply styles.
  - Declarations: styles to be applied.

```css
p {
  color: red;
  text-align: center;
}
```

- **CSS rules and declerations**
  - Rules: combinations of selectors and declarations.
- **Applying CSS styles to HTML elements**
  - Inline styles: used within HTML tags.
  - Internal styles: used within `<style>` tags.
  - External styles: linked to the HTML file via `<link>` tags.
- **CSS comments**
  - Comments: start with /_ and end with _/.

## Part-2: Box Model & Dimensions

- **Understanding the box model**
  - Box model: content, padding, border, and margin.
- **Controlling element dimensions**
  - Width and height properties.
  - Box-sizing property to control how dimensions are calculated.

```css
.box {
  width: 100px;
  height: 100px;
  padding: 20px;
  border: 5px solid black;
  box-sizing: border-box;
}
```

## Part-3: Positioning & Floating

- **Positioning elements**
  - Static (default), relative, absolute, fixed positioning.

```css
.box {
  position: relative;
  top: 20px;
  left: 20px;
}
```

- **Floating elements**
  - Float left, right, or none.

```css
.image {
  float: right;
}
```

## Part-4: Display Property & Layout Techniques

- **Display property**
  - `block`, `inline`, `inline-block`, `flex`, `grid`.

```css
.box {
  display: flex;
}
```

- **CSS layout techniques**
  - Floats, flexbox, grid.

```css
.container {
  display: flex;
}
```

## Part-5: Styling Text

- **Setting font family, size, and weight**

```css
p {
  font-family: Arial, sans-serif;
  font-size: 16px;
  font-weight: bold;
}
```

- **Text alignment and indentation**

```css
p {
  text-align: center;
  text-indent: 50px;
}
```

- **Text decoration**

```css
p {
  text-decoration: underline;
}
```

- **Line height and spacing**

```css
p {
  line-height: 1.6;
  letter-spacing: 2px;
}
```

## Part-6: Advanced CSS Techniques

- **Transparency and opacity**

```css
.box {
  background-color: red;
  opacity: 0.5;
}
```

- **Pseudo-classes and pseudo-elements**

```css
p:hover {
  color: blue;
}

p::before {
  content: "Read this - ";
}
```

- **Overriding styles and using !important**

```css
p {
  color: red !important;
}
```

## Part-7: CSS Animations

- **Timing functions**

```css
.animation {
  transition-timing-function: ease-in;
}
```

- **CSS animation keyframes and properties**

```css
@keyframes example {
  0% {
    background-color: red;
  }
  100% {
    background-color: yellow;
  }
}

.animation {
  animation-name: example;
  animation-duration: 4s;
}
```

- **Delaying and repeating animations**

```css
.animation {
  animation-delay: 2s;
  animation-iteration-count: infinite;
}
```

## Part-8: Responsive Design

- **Media queries and responsive breakpoints**

```css
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
```
