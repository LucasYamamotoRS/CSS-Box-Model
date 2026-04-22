# CSS Box Model Study Project 

A focused web development project designed to demonstrate the fundamental concepts of the **CSS Box Model**. This project visualizes how margins, borders, and widths interact to create a structured "Poster" layout.

** Live Demo:** [View the Project](https://lucasyamamotors.github.io/CSS-Box-Model/)

##  Learning Objectives

The goal of this project was to practice:
* **Width & Centering**: Using percentage-based widths and auto-calculated margins.
* **Border Property**: Implementing visible boundaries on elements.
* **Typography**: Integrating external Google Fonts and manipulating text scales.
* **Dark Mode Aesthetics**: Working with high-contrast color schemes.

## 📋 Box Model Implementation

In this project, the **Box Model** is applied to the `.poster` and `.cheers` classes to control the layout:

1. **Content**: The text and GIF.
2. **Border**: A `5px solid white` border applied to the image, adding to its total size.
3. **Margin**: 
   * `100px` top margin to push the content down from the top of the viewport.
   * `25%` left margin used to center the `50%` width container (25% left + 50% width + 25% right = 100%).

##  Project Structure

```text
.
├── index.html          # HTML5 structure
├── style.css           # CSS Box Model styling
└── assets/
    └── images/         # Local assets
