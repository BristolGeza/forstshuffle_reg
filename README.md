# Forest Shuffle

**Forest Shuffle** is a web-based application that allows players to keep track of various statistics in a Forest Shuffle Board Game. The application features a simple user interface where users can input numbers for each player and see the calculated sums.

## Features

- **Player Tracking:** Keep track of the statistics for multiple players (Lenke, Gaspar, Zsofi, and Geza).
- **Dynamic Updates:** Automatically calculate and display the sum of the inputs for each player.
- **Responsive Design:** The application is designed to be responsive and works well on different screen sizes.

## Code Overview

### HTML Structure

- The document is structured with an HTML table that allows players to input their statistics.
- There are four categories of statistics: Trees, Top-Bottom, Left-Right, and In Cave.
- The table dynamically updates the sum of the input values for each player.

### CSS Styles

- The application uses a forest-themed background image.
- The styles are designed to be simple, clean, and visually appealing.
- The application ensures that the text is readable by setting appropriate colors and font styles.

### JavaScript Functionality

- The `calculateSummary` function dynamically calculates and updates the sum of the input values for each player.
- The function listens for input events and updates the sum values in real-time.

## How to Use

1. Open the `index.html` file in your web browser.
2. Enter the statistics for each player in the input fields under the corresponding categories.
3. The sum of the values for each player will be automatically calculated and displayed in the "Sum" row.

## File Structure


- `assets/images/images.jpeg`: Background image used in the application.
- `index.html`: Main HTML file containing the structure and logic of the application.
- `README.md`: Documentation file providing an overview of the application.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).


