# 🥛 Milk Tracker Pro

> **100% Vibe Code.** No frameworks. No build steps. No servers. Just pure, aesthetic utility.

A beautiful, single-file HTML5 application designed to track daily milk deliveries, calculate monthly costs, and look good doing it. Built with modern glassmorphism UI and offline-first local storage.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Size](https://img.shields.io/badge/size-<10kb-success)
![Vibe](https://img.shields.io/badge/vibe-immaculate-purple)

## ✨ Features

* **Glassmorphism UI:** Modern, translucent aesthetic with smooth micro-animations and floating background elements.
* **Smart Calendar:** Interactive grid view with instant visual feedback for logged days.
* **Cost Calculator:** Set your price per liter once, and get automatic real-time monthly totals.
* **Touch Optimized:**
    * **Month Scrubber:** Slide across the top to quickly jump between months.
    * **Quantity Slider:** Drag to adjust milk quantity (0.5L - 5L) with haptic-like visual feedback.
* **Offline Persistence:** Uses LocalStorage to save your data forever in your browser. No internet required.
* **Responsive:** Works perfectly on mobile phones and desktop screens.

## 🚀 How to Use

1.  **Download:** Save the `index.html` file to your computer or phone.
2.  **Run:** Double-click the file to open it in any modern web browser (Chrome, Safari, Firefox, Edge).
3.  **Setup:** Click the **Settings (⚙️)** icon in the top right to set your **Price Per Liter**.
4.  **Track:** Tap any date to log milk. Use the slider to adjust quantity.
5.  **Review:** See your total liters and total cost update instantly at the top.

## 🛠️ Technical Details

This is a **Single File Component (SFC)** in the truest sense.

* **HTML5:** Semantic structure.
* **CSS3:** CSS Variables, Flexbox, Grid, Backdrop-filter, Keyframe animations.
* **JavaScript:** Vanilla ES6+. Zero external libraries.

### The "Vibe Code" Philosophy
This project was built with the **100% Vibe Code** standard:
1.  **Copy-Paste Deploy:** If it can't run by just opening the file, it's too complex.
2.  **Aesthetics First:** Utility doesn't have to be ugly.
3.  **Zero Bloat:** No `node_modules`, no webpack, no complexity.

## 🎨 Customization

Want to change the colors? Open the file in a text editor and look for the `:root` variables at the top of the `<style>` block:

```css
:root {
    --bg-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%); /* Change background */
    --accent: #00d2ff; /* Change highlight color */
}
