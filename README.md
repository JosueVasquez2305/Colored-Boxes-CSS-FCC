# Colored Boxes Project 🎨

A modern, clean, and interactive web interface designed to showcase advanced CSS coloring methodologies, structural layouts with Flexbox, and subtle 3D micro-interactions.

---

## 🚀 Features

* **Responsive Flexbox Layout:** Uses a flexible container grid to keep elements centered and perfectly aligned across different screen dimensions.
* **Advanced Color Formatting:** Implements a variety of web color spaces to demonstrate deep knowledge of modern CSS styling.
* **Dynamic Visual Depth:** Text and elements feature custom shadows that simulate elevation and real-world lighting.
* **Modern Micro-interactions:** Features a polished `:hover` effect that smoothly elevates the boxes using transitions on position and shadow properties.

---

## 🎨 Color Theory & Technologies Demonstrated

This project serves as a practical application of different color syntax and styling techniques in CSS:

* **Hexadecimal (`#HEX`):** Applied for precise, solid color rendering (e.g., `#FF9599` and `#55b6ff`).
* **RGB (`rgb()`):** Used with standard modern functional notation (`rgb(155 220 200)`).
* **HSL (`hsl()`):** Demonstrated through hue, saturation, and lightness coordinates to define deep, rich tones (`hsl(200, 100%, 25%)`).
* **Alpha Channel / Transparency (`rgba()`):** Implemented in both text and box shadows using low opacity values (`rgba(0, 0, 0, 0.35)`) to achieve organic, blending depths rather than rigid black strokes.

---

## 🛠️ CSS Architecture Highlights

```css
/* Smooth synchronization of movement and shadow blending */
.color-box {
  width: 150px;
  height: 150px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* Vertical translation combined with depth expansion */
.color-box:hover {
  transform: translateY(-8px);
  box-shadow: 12px 12px 20px rgba(0, 0, 0, 0.35);
}
📦 How to Run Locally
Clone this repository:

Bash
git clone [https://github.com/JosueVasquez2305/Colored-Boxes-CSS-FCC.git](https://github.com/JosueVasque2305/Colored-Boxes-CSS-FCC.git)
Navigate into the project folder:

Bash
cd Colored-Boxes-CSS-FCC
Open index.html in your favorite web browser.


***
