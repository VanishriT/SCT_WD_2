# SCT_WD_2

# Modern Calculator Web Application

A sleek, interactive, and fully functional web-based calculator built with HTML, CSS, and Vanilla JavaScript. This project goes beyond standard functionality by incorporating a highly visual **glassmorphism** design, an animated gradient background, and an interactive **particle system** that reacts to mouse movements.

## ✨ Features

* **Standard Arithmetic:** Perform addition, subtraction, multiplication, and division with floating-point precision.
* **Glassmorphism UI:** A modern interface utilizing background blur, semi-transparent panels, and soft shadows for a premium look.
* **Interactive Particle System:** A custom-built, lightweight JavaScript particle system in the background that smoothly repels from the user's cursor.
* **Calculation History:** * Keeps track of your previous calculations.
* **Keyboard Support:** Fully accessible via keyboard.
  * `0`-`9` and `.` for numbers
  * `+`, `-`, `*`, `/` for operations
  * `Enter` or `=` to calculate
  * `Backspace` to delete the last digit
  * `Escape` to clear all (AC)
* **Responsive Design:** Scales perfectly for both desktop and mobile screens.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and layout.
* **CSS3:** * CSS Grid & Flexbox for layout management.
  * Keyframe animations for the shifting gradient background.
  * Backdrop-filters for the frosted glass effect.
* **Vanilla JavaScript:** * `Calculator` class for handling mathematical logic and state.
  * `ParticleSystem` class for canvas-free DOM-based particle animation.
  * `localStorage` API for saving calculation history.
  * Event Listeners for mouse tracking and keyboard inputs.

## 📁 Project Structure

The entire application is consolidated into a single file for maximum portability:
* `calculator.html`: Contains the structural markup, inline `<style>` block for all CSS/animations, and the `<script>` block containing the application logic.

## 📝 Usage Tips

* **History Panel:** Click the 📊 button to open your past calculations. If you want to reuse a result, simply click on the equation in the history list!
* **Keyboard:** For the fastest experience, use your numpad to type out equations and hit `Enter`.
