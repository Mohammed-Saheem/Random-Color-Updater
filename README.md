# 🎨 Random Color Generator

A fun and interactive web app that generates a random RGB color every time you click the button.  
It changes the background of the display box, shows the color code, and updates the text color dynamically.

---

## 🚀 Features
- Generates **random RGB colors** (`rgb(red, green, blue)`).
- Updates **background color** of a box.
- Displays the **exact color code**.
- Smooth **animations and transitions** for better UI.
- Responsive and modern design.

---

## 🖥️ Technologies Used
- **HTML5** → Structure of the app.
- **CSS3** → Styling, layout, and animations.
- **JavaScript (ES6)** → Core functionality (random color generation & DOM updates).

---

## ⚡ JavaScript Functionality (Key Highlight)
1. `getRandomColor()` → Generates a random RGB color using `Math.random()`.
2. `btn.addEventListener("click", ...)` → Detects button click and triggers color update.
3. Updates:
   - **Background color** of `.color-box`
   - **Displayed text** with the color code
   - **Text color** to match the generated color.

```js
function getRandomColor() {
  let red = Math.floor(Math.random() * 256);
  let green = Math.floor(Math.random() * 256);
  let blue = Math.floor(Math.random() * 256);

  return `rgb(${red}, ${green}, ${blue})`;
}
