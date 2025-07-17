# DAY 3 (Summary/Quick Notes)

**Todays Topics Covered:**

### 📌 What Is CSS?
- **CSS** stands for *Cascading Style Sheets*.
- It defines how HTML elements are styled—colors, fonts, layout, spacing, and responsiveness.
- Analogy: HTML is like nouns & verbs; CSS adds the adjectives & adverbs.

---

## 🎨 Applying CSS – **Three Methods**

| Method        | Syntax Example | Pros | Cons |
|---------------|----------------|------|------|
| **Inline CSS** | `<p style="color: blue;">Text</p>` | Quick for small tweaks | Mixes content & style; hard to maintain |
| **Internal CSS** | `<style> h1 { color: red; } </style>` in `<head>` | Centralized per page | Not reusable across pages |
| **External CSS** *(Best Practice)* | `<link rel="stylesheet" href="style.css">` | Separates structure & style; reusable | Requires extra file |

---

## 🧩 CSS Syntax Overview

- Rule = **Selector + Declaration Block**
```css
selector {
  property: value;
  property: value;
}
```

- **Selector** targets HTML elements (e.g., `p`, `.class`, `#id`)
- **Declaration Block** contains:
  - **Property** (e.g., `color`, `font-size`)
  - **Value** (e.g., `blue`, `16px`)
  - Separated by `:` and ended with `;`

---

## 🎯 Selectors Breakdown

| Selector Type       | HTML Example                     | CSS Example                          | Notes |
|---------------------|----------------------------------|--------------------------------------|-------|
| **Element Selector** | `<p>Text</p>`                    | `p { color: green; }`                | Targets all `<p>` |
| **Class Selector**   | `<p class="highlight">Text</p>` | `.highlight { background: yellow; }` | Use for reusable styles |
| **ID Selector**      | `<div id="main-header"></div>`  | `#main-header { font-weight: bold; }` | Must be unique |
| **Universal Selector** | (any HTML)                    | `* { margin: 0; padding: 0; }`        | Affects all elements |
| **Group Selector**   | `<h1>`, `<h2>`, `<p>`           | `h1, h2, p { font-family: Arial; }`  | Targets multiple types |
| **Descendant Selector** | `<div><p></p></div>`        | `div p { color: purple; }`           | Targets nested elements |
