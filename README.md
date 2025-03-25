# Analog-Clock

This is a simple analog clock built using HTML, CSS, and JavaScript. It displays the current time by rotating the hour, minute, and second hands every second, with a clean and stylish design.

## 🎯 Live Demo  
Check out the clock in action here: **[Analog Clock Demo](https://pragyat-nikunj.github.io/Analog-Clock/)**  

## Features

- **Real-Time Update:** The clock updates every second using JavaScript's `setInterval` function.
- **Accurate Hand Movement:**  
  - **Hour Hand:** Rotates based on the hour and a fraction of the minutes (`30 * hours + minutes / 2`).
  - **Minute Hand:** Rotates by 6 degrees for every minute.
  - **Second Hand:** Rotates by 6 degrees for every second.
- **Custom Styling:**  
  - The clock face has a semi-transparent background, a border, and a shadow effect.
  - The hour, minute, and second hands use CSS variables for easy styling.
- **Number Placement:** The numbers 1 to 12 are positioned around the clock face using CSS custom properties and transforms.

## How It Works

1. **HTML Structure:**  
   The `index.html` file contains a `div` for the clock and its hands. It also includes numbers from 1 to 12.
   
2. **Styling with CSS:**  
   The `style.css` file designs the circular clock, positions the numbers, and styles the hands.

3. **Time Calculation with JavaScript:**  
   The `script.js` file fetches the current time and calculates the correct rotation for each hand:
   - Hour hand: `30 * hours + minutes / 2` degrees.
   - Minute hand: `6 * minutes` degrees.
   - Second hand: `6 * seconds` degrees.  
   The `setInterval` function updates the clock every second.

## 🚀 How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Pragyat-Nikunj/Analog-Clock.git
   ```

2. **Open the Project:**
   Open the `index.html` file in your browser.

## 🎨 Customization

- **Modify Colors and Sizes:**  
  Edit the inline CSS variables in `index.html` or update `style.css` to change the appearance.
- **Adjust Clock Face Styling:**  
  Modify the CSS properties for the border, shadow, or font styles.

## 📌 Conclusion

This project is a beginner-friendly example of how to create an analog clock using basic web technologies. It demonstrates dynamic DOM manipulation, CSS styling, and JavaScript timing functions effectively.

---

