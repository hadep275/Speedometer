# Speedometer

A visually enhanced and modernized speedometer built with HTML, CSS, and JavaScript using the [gauge.js](https://bernii.github.io/gauge.js/) library. This speedometer provides a sleek and responsive user interface for monitoring values within a range of 0 to 2500.

![Speedometer Demo](demo/speedometer-demo.gif)

## Features

- **Modern Design:** The speedometer has been redesigned for a more modern and visually appealing look.
- **Responsive:** The UI is responsive, ensuring a consistent experience across various devices and screen sizes.
- **User-friendly Controls:** Easily input values through a user-friendly input field and try the speedometer with a single click.
- **Error Handling:** Robust error handling to alert users when an invalid number is entered.

## Live Demo

Experience the speedometer live! Check out the [browser demo](#) to interact with the speedometer and see its features in action.

## Video Demo

Watch a detailed demonstration of the speedometer by following this [video demo link](#).

## How to Use

1. Clone this repository:

    ```bash
    git clone <repository-url>
    ```

2. Open the `index.html` file in your preferred web browser.

3. Enter a numeric value between 0 and 2500 in the input field.

4. Click the "Try" button to update the speedometer with the entered value.

## Customization

Feel free to customize the speedometer further by adjusting the styles or modifying the gauge.js options in the script section of the HTML file.

```javascript
var opts = {
  lines: 12,
  angle: 0.0,
  lineWidth: 0.44,
  pointer: {
    length: 0.5,
    strokeWidth: 0.035,
    color: "red",
  },
  limitMax: false,
  colorStart: "blue",
  colorStop: "#eeff00",
  StrokeColor: "#E0E0E0",
  generateGradient: true,
};
```

## Contributors

- [Your Name]

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute to make this speedometer even more amazing!
