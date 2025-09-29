# Array Methods Demo (ES6 + SCSS Enhancements)

This project is part of my frontend internship curriculum.  
It demonstrates the use of **ES6 features** and progressively applies **modern styling using SCSS (which compiles to CSS)**.

- **Week 1 Deliverable:** Demonstrate ES6 features (arrays, arrow functions, let/const, scope) with a simple interactive webpage.
- **Week 2 Deliverable:** Enhance the same webpage with **CSS properties, selectors, text/fonts, images in CSS, box model, layout, flexbox, and responsiveness**.
- **Week 3 Deliverable:** Style and structure the same webpage using SCSS.

---

## 📝 Week 1 Recap

The Week 1 implementation focused on core JavaScript (ES6) concepts:

- Demonstrating array methods (`map`, `filter`, `reduce`, `forEach`) on the array `[1, 2, 3, 4, 5]`.
- Implementing logic with **arrow functions** and `let`/`const`.
- Each method is triggered by a button, and the result is displayed with a short explanation.

---

## Week 2 Enhancements

In Week 2, I extended the project with **CSS styling and layout concepts**:

---

## 🎨 Week 3 Enhancements (Using SCSS)

For Week 3, SCSS was introduced to organize and scale styling more cleanly.  
The compiled CSS is applied to the same HTML structure.

### ✅ SCSS Features Used

- **Nesting** – for cleaner selector structure.
- **Variables** – for reusable colors and spacing.
- **Partials & Organization** – separating styling logic for readability.
- **SCSS Compilation** – converted to standard CSS for browser use.

### ✅ Styling Concepts Implemented

| Concept             | Description                                                                                |
| ------------------- | ------------------------------------------------------------------------------------------ |
| **CSS Properties**  | Used `color`, `background-color`, `margin`, `padding`, `border`, and `font-size`.          |
| **CSS Selectors**   | Applied element (`p`, `button`), class (`.button-group`), and ID (`#output`) selectors.    |
| **Text & Fonts**    | Customized `font-family`, `font-size` (using `rem`/`em`), and line-height for readability. |
| **Images in CSS**   | Added a decorative image using `background-image` in the output box.                       |
| **Box Model**       | Demonstrated margin, padding, border, and content spacing clearly.                         |
| **px vs em vs rem** | Showed differences in font sizing approaches.                                              |
| **Layout**          | Structured page sections (`header`, `buttons`, `output`).                                  |
| **Flexbox**         | Used `display: flex` for button arrangement with wrapping.                                 |
| **Responsiveness**  | Added media queries to make the layout mobile-friendly.                                    |

---

## 📁 Project Structure

```
array-methods-demo/
│── index.html         # Main HTML file
│── scss/
│   ├── _base.scss   # global styles
│   ├── _variables.scss   # SCSS variables (colors, fonts, spacing)
│   ├── _layout.scss      # Flexbox and layout styles
│   ├── _components.scss  # Reusable components
│   └── main.scss        # Main SCSS file importing partials
│── css/
│   └── main.css         # Compiled CSS from SCSS
│── README.md
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Ensure you have **Sass/SCSS installed** globally or in your project:
   ```bash
   npm install -g sass
   ```
3. Compile SCSS to CSS (if not already compiled):
   ```bash
   sass scss/main.scss css/main.css
   ```
4. Open `index.html` in any modern browser (Chrome, Firefox, Edge).
5. Click any of the array method buttons to see the result and the styled interface.

---

## 🧪 Example (map)

When clicking **map()**, the output displays:

```
map(): 2,4,6,8,10
map() creates a new array by applying a function to each element.
Here, each number was doubled.
```

Now, the result box is styled with borders, padding, background color, and responsive behavior using SCSS.

---

## 🧰 Tools & Technologies

- **HTML5**
- **JavaScript (ES6)**
- **SCSS (Sass)** — compiled to CSS
- **Flexbox** for layout
- **Media Queries** for responsiveness
