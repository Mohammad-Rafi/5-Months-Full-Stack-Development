# DAY 2 (Summary/Quick Notes)

**Todays Topics Covered:**

## 💬 HTML Forms (User Input)

HTML forms allow users to enter and submit data on a webpage.

### Key Tags & Attributes
- `<form>`  
  - `action`: Destination URL for form data  
  - `method`: HTTP method (`GET`, `POST`)

- `<input>`  
  - `type`: Defines input style (`text`, `email`, `password`, `number`, `checkbox`, `radio`, `submit`)  
  - `name`: Key sent to server  
  - `id`: Unique identifier  
  - `value`: Default value  
  - `placeholder`: Hint inside input  
  - `required`: Marks field as mandatory

- `<textarea>`  
  - Multi-line text input  
  - Attributes: `name`, `id`, `rows`, `cols`, `placeholder`, `required`

- `<button>`  
  - Custom button actions  
  - `type`: `submit`, `reset`, `button`

- `<label>`  
  - Links text to form elements  
  - `for`: Should match the input’s `id` for accessibility

- `<select>` & `<option>`  
  - Dropdown list  
  - Attributes: `name`, `multiple` (for `<select>`), `value`, `selected` (for `<option>`)

---

## 🧠 Semantic HTML5

Semantic tags describe the purpose of the content, making pages more accessible and readable.

### Benefits
- Improves accessibility (e.g., screen readers)
- Enhances SEO
- Easier code maintenance

### Common Tags & Uses

| Tag        | Purpose                                       | Attributes                       |
|------------|-----------------------------------------------|----------------------------------|
| `<header>` | Intro content (logo, nav, heading)            | `id`, `class`                    |
| `<nav>`    | Navigation links                              | `id`, `class`, `aria-label`     |
| `<main>`   | Main content of the page                      | `id`, `class`                    |
| `<article>`| Independent item (blog, post, comment)        | `id`, `class`                    |
| `<section>`| Groups related content                        | `id`, `class`, `aria-label`     |
| `<aside>`  | Tangential info (ads, side notes, quotes)     | `id`, `class`                    |
| `<footer>` | Footer area (credits, links)                  | `id`, `class`                    |

📘 **Analogy**: Like chapters and elements of a well-organized book—semantic tags structure web pages for clarity and purpose.



