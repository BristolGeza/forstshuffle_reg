# Forest Shuffle

**Forest Shuffle** is a web-based application designed to track and manage players' statistics in a forest-themed game. The application features a user-friendly interface where players can enter their names and scores, with the system dynamically calculating and displaying the sum of their inputs and determining the winner.

## Features

- **Player Input:** Players can enter their names and scores in different categories.
- **Dynamic Calculation:** The application automatically calculates the sum of scores for each player and identifies the winner.
- **Responsive Design:** The application is styled for readability and usability across different devices.

## Code Overview

### HTML Structure

- The document is structured with an HTML table that allows players to input their names and scores.
- Four categories of scores are tracked: Trees, Top-Bottom, Left-Right, and In Cave.
- The application dynamically updates the sum of the scores for each player and displays the winner.

### CSS Styles

- The application uses a forest-themed background image to enhance the visual experience.
- Styles are designed to ensure readability and accessibility, with appropriate colors and font choices.
- Responsive layout ensures the application looks good on various screen sizes.

### JavaScript Functionality

- The `calculateSummary` function calculates and updates the sum of the scores for each player.
- The function listens for input events and updates the displayed scores and winner in real-time.

## How to Use

1. Open the `index.html` file in your web browser.
2. Enter the players' names in the input fields under the "Players" column.
3. Enter the scores for each category (Trees, Top-Bottom, Left-Right, In Cave) in the respective input fields.
4. The sum of the scores for each player will be automatically calculated and displayed in the "Sum" row.
5. The winner will be displayed at the bottom of the page.

## File Structure


- `assets/images/images.jpeg`: Background image used in the application.
- `index.html`: Main HTML file containing the structure, styles, and logic of the application.
- `README.md`: Documentation file providing an overview of the application.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

