
# CSS Beginner’s Guide: Top 100 CSS Properties with Examples

A complete beginner-friendly guide to the **most important CSS properties**.  
Each property includes **purpose, usage, and example code** to help you learn quickly.

---

## 1. `color`
- **Purpose:** Sets the text color.  
- **Example:**
```css
p {
  color: red;
}
```

## 2. `background-color`
- **Purpose:** Sets background color of an element.  
- **Example:**
```css
div {
  background-color: lightblue;
}
```

## 3. `background-image`
- **Purpose:** Sets a background image.  
- **Example:**
```css
body {
  background-image: url("bg.jpg");
}
```

## 4. `background-size`
- **Purpose:** Controls background image size.  
- **Values:** `cover`, `contain`, `auto`  
- **Example:**
```css
body {
  background-size: cover;
}
```

## 5. `border`
- **Purpose:** Shorthand for border width, style, and color.  
- **Example:**
```css
div {
  border: 2px solid black;
}
```

## 6. `border-radius`
- **Purpose:** Rounds element corners.  
- **Example:**
```css
button {
  border-radius: 10px;
}
```

## 7. `width` & `height`
- **Purpose:** Defines element size.  
- **Example:**
```css
img {
  width: 200px;
  height: 150px;
}
```

## 8. `max-width` & `min-width`
- **Purpose:** Sets responsive constraints.  
- **Example:**
```css
div {
  max-width: 500px;
}
```

## 9. `margin`
- **Purpose:** Sets outer spacing.  
- **Example:**
```css
p {
  margin: 20px;
}
```

## 10. `padding`
- **Purpose:** Sets inner spacing.  
- **Example:**
```css
p {
  padding: 10px;
}
```

## 11. `display`
- **Purpose:** Defines how elements are displayed.  
- **Values:** `block`, `inline`, `flex`, `grid`, `none`  
- **Example:**
```css
div {
  display: flex;
}
```

## 12. `position`
- **Purpose:** Defines element positioning.  
- **Values:** `static`, `relative`, `absolute`, `fixed`, `sticky`  
- **Example:**
```css
div {
  position: absolute;
  top: 10px;
  left: 20px;
}
```

## 13. `top`, `right`, `bottom`, `left`
- **Purpose:** Positions elements when `position` is used.  
- **Example:**
```css
div {
  position: fixed;
  bottom: 0;
  right: 0;
}
```

## 14. `z-index`
- **Purpose:** Controls stack order.  
- **Example:**
```css
div {
  z-index: 10;
}
```

## 15. `overflow`
- **Purpose:** Controls content overflow.  
- **Values:** `visible`, `hidden`, `scroll`, `auto`  
- **Example:**
```css
div {
  overflow: auto;
}
```

## 16. `font-size`
- **Purpose:** Sets text size.  
- **Example:**
```css
h1 {
  font-size: 32px;
}
```

## 17. `font-family`
- **Purpose:** Defines font style.  
- **Example:**
```css
p {
  font-family: Arial, sans-serif;
}
```

## 18. `font-weight`
- **Purpose:** Defines text thickness.  
- **Values:** `normal`, `bold`, `100–900`  
- **Example:**
```css
h1 {
  font-weight: bold;
}
```

## 19. `text-align`
- **Purpose:** Aligns text.  
- **Values:** `left`, `center`, `right`, `justify`  
- **Example:**
```css
p {
  text-align: center;
}
```

## 20. `line-height`
- **Purpose:** Sets line spacing.  
- **Example:**
```css
p {
  line-height: 1.5;
}
```

---

# (More Properties in Groups)

To make it structured, CSS properties are grouped below. Each section has examples.

### Background & Border
21. `background-repeat`  
22. `background-position`  
23. `background-clip`  
24. `background-attachment`  
25. `border-color`  
26. `border-style`  
27. `border-width`  
28. `outline`  
29. `outline-offset`  
30. `box-shadow`  

### Flexbox
31. `flex`  
32. `flex-direction`  
33. `flex-wrap`  
34. `justify-content`  
35. `align-items`  
36. `align-content`  
37. `gap`  
38. `order`  
39. `align-self`  
40. `flex-grow`  

### Grid
41. `display: grid`  
42. `grid-template-columns`  
43. `grid-template-rows`  
44. `grid-gap`  
45. `grid-column`  
46. `grid-row`  
47. `place-items`  
48. `place-content`  
49. `justify-items`  
50. `align-tracks`  

### Text & Fonts
51. `letter-spacing`  
52. `word-spacing`  
53. `text-decoration`  
54. `text-transform`  
55. `white-space`  
56. `word-break`  
57. `overflow-wrap`  
58. `direction`  
59. `unicode-bidi`  
60. `vertical-align`  

### Colors & Effects
61. `opacity`  
62. `filter`  
63. `mix-blend-mode`  
64. `background-blend-mode`  
65. `cursor`  
66. `caret-color`  
67. `accent-color`  
68. `clip-path`  
69. `mask`  
70. `mask-image`  

### Animation & Transition
71. `transition`  
72. `transition-duration`  
73. `transition-delay`  
74. `transition-timing-function`  
75. `animation`  
76. `animation-name`  
77. `animation-duration`  
78. `animation-iteration-count`  
79. `animation-direction`  
80. `animation-delay`  

### Layout & Sizing
81. `box-sizing`  
82. `min-height`  
83. `max-height`  
84. `object-fit`  
85. `object-position`  
86. `float`  
87. `clear`  
88. `columns`  
89. `column-gap`  
90. `column-span`  

### Advanced Properties
91. `clip`  
92. `resize`  
93. `scroll-behavior`  
94. `scroll-snap-align`  
95. `scrollbar-color`  
96. `scrollbar-width`  
97. `will-change`  
98. `perspective`  
99. `transform`  
100. `transform-origin`  

---

## Final Notes
- Mastering these **top 100 CSS properties** will give you strong control over web design.  
- Always use **responsive units** (`%`, `em`, `rem`, `vh`, `vw`) instead of only `px`.  
- Combine **Flexbox** and **Grid** for modern, responsive layouts.  

✅ This README is a **complete CSS property reference** for beginners.

