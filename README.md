# Ferris Wheel

This project is a simple HTML and CSS exercise that creates an animated Ferris wheel. The Ferris wheel is styled using CSS animations to rotate continuously, and the cabins change colors as they move around the wheel. This project is part of the curriculum on [freeCodeCamp.org](https://www.freecodecamp.org/), designed to help learners practice CSS animations and transformations.

## Project Structure

### HTML

The `index.html` file contains the basic structure of the Ferris wheel. It includes:

- **`.wheel`**: The main container for the Ferris wheel.
- **`.line`**: The lines that form the spokes of the Ferris wheel.
- **`.cabin`**: The cabins attached to the Ferris wheel.

### CSS

The `styles.css` file is responsible for styling the Ferris wheel and its animation. It includes:

- **`.wheel`**: Styles for the Ferris wheel container, including its size, border, and rotation animation.
- **`.line`**: Styles for the spokes of the Ferris wheel, positioned and rotated to create the wheel effect.
- **`.cabin`**: Styles for the cabins, including their size, color, and position around the Ferris wheel.
- **Keyframes**:
  - **`@keyframes wheel`**: Animates the rotation of the Ferris wheel.
  - **`@keyframes cabins`**: Animates the color changes and rotation of the cabins.

### CSS Details

- **`.wheel`**:
  - `border`: 2px solid black.
  - `border-radius`: 50% to create a circular shape.
  - `animation`: Rotates the wheel continuously.
- **`.line`**:
  - `background-color`: Black.
  - `width` and `height`: Defines the lines forming the spokes.
  - `transform`: Rotates the lines to create the effect of a Ferris wheel.
- **`.cabin`**:
  - `background-color`: Red, changing to yellow and purple during animation.
  - `position`: Absolute to place cabins around the wheel.
  - `animation`: Changes colors and rotates the cabins.

### Animation and Layout

- **Ferris Wheel Rotation**: The wheel rotates 360 degrees continuously using the `wheel` keyframes animation.
- **Cabin Color Change**: Cabins change color between red, yellow, and purple during the animation cycle using the `cabins` keyframes animation.

## How to Run the Project

1. Clone or download this project.
2. Open the `index.html` file in a web browser to view the animated Ferris wheel.

## Contributions

Contributions are welcome. Feel free to fork the project and submit a pull request with improvements or enhancements.

---

This project is part of the curriculum on [freeCodeCamp.org](https://www.freecodecamp.org/), designed to help learners practice CSS animations and transformations by creating a dynamic Ferris wheel.
