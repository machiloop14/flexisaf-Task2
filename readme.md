# Array Methods Demo (ES6 + CSS Enhancements)

This project is part of my frontend internship curriculum.

- **Week 1 Deliverable:** Demonstrate ES6 features (arrays, arrow functions, let/const, scope) with a simple interactive webpage.
- **Week 2 Deliverable:** Enhance the same webpage with **CSS properties, selectors, text/fonts, images in CSS, box model, layout, flexbox, and responsiveness**.

---

## Week 1 Recap

The Week 1 version of this project showed how ES6 array methods (`map`, `filter`, `reduce`, `forEach`) work on the array `[1, 2, 3, 4, 5]`. Each method could be executed by clicking a button, and the result was displayed along with a short description.

---

## Week 2 Enhancements

In Week 2, I extended the project with **CSS styling and layout concepts**:

### ✅ CSS Properties

- Used `color`, `background-color`, `margin`, `padding`, `border`, and `font-size`.

### ✅ CSS Selectors

- Applied **element selectors** (`p`, `button`),
- **class selectors** (`.button-group`),
- **id selectors** (`#output`).

### ✅ Text and Font

- Changed font family (`Arial, sans-serif`),
- Adjusted font sizes with `rem` and `em`,
- Controlled line height for readability.

### ✅ Images in CSS

- Added a decorative image using `background-image` in the output box.

### ✅ Box Model

- Applied `margin`, `padding`, `border`, and `content` styles to the output container.

### ✅ px vs em vs rem

- Demonstrated font sizing differences (`px`, `em`, `rem`) in text elements.

### ✅ Layout

- Structured page sections (`h1`, paragraph, button group, output box).

### ✅ Flexbox

- Used `display: flex` and `gap` for arranging buttons.
- Allowed wrapping for responsiveness.

### ✅ Responsiveness

- Added a media query (`max-width: 600px`) to adjust text size and stack buttons vertically on smaller screens.

---

## Project Structure

│── index.html # main html file
│── style.css # main css file

---

## How to Run

1. Clone or download this project.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, etc.).
3. Click any button to run an array method and see styled results.

---

## Example (map)

When clicking **map()**, the output shows:
map(): 2,4,6,8,10
map() creates a new array by applying a function to each element.
Here, each number was doubled.

## Future Improvements

- Add **object examples** with methods to cover Week 1 topics more fully.
- Let users **enter their own array** instead of using `[1, 2, 3, 4, 5]`.
- Explore **CSS Grid** as an alternative layout method in future weeks.
