# Rotating Animation Design
##Demo
![animation](https://github.com/Dirojini/rotating-animation/blob/e6dcd3106782a1e4212fe38d67bbb8b9206d3347/Screenshot%202024-12-24%20114303.png)
A sleek and smooth rotating animation design created using HTML and CSS. This animation can be used for elements like cards, modals, or transitions between quiz questions.

## Features

- **Smooth Rotation**: Elements rotate seamlessly in and out of view.
- **Customizable Speed**: Easily adjust the rotation duration and delay.
- **Responsive Design**: Works across different screen sizes.
- **Reusable**: Simple and modular CSS for easy integration into any project.

## Technologies Used

- **HTML** – For the structure of the rotating element.
- **CSS** – For the animation and styling.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Dirojini/routating-animation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd rotating-animation
   ```
3. Open the `index.html` file in your web browser.

## File Structure

```
rotating-animation/
│
├── index.html       # Main HTML file
└── rotate.css       # CSS for rotating animation
```

## Sample Rotate Animation (rotate.css)

```css
.rotate-enter {
  transform: rotateY(90deg);
  opacity: 0;
}

.rotate-enter-active {
  transform: rotateY(0);
  opacity: 1;
  transition: transform 0.5s ease, opacity 0.5s ease;
}

.rotate-exit {
  transform: rotateY(0);
  opacity: 1;
}

.rotate-exit-active {
  transform: rotateY(-90deg);
  opacity: 0;
  transition: transform 0.5s ease, opacity 0.5s ease;
}
```

## Screenshots



## Future Enhancements

- **Multiple Rotation Axes** (X, Y, Z)
- **3D Effects**
- **Customization with JavaScript**
- **Hover and Click Animations**

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

