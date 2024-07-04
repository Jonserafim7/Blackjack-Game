# Blackjack Game

## Project Overview

The Blackjack Game is a web-based application that simulates a simple version of the popular casino card game, Blackjack. The game allows players to draw cards, calculate their sum, and check for a win or loss condition based on standard Blackjack rules. This project provides a hands-on experience with fundamental web development concepts and game logic implementation.

## Features

- **Start Game**: Initialize a new game with two randomly drawn cards.
- **Draw New Card**: Add a new card to your hand and update the sum.
- **Game Messages**: Display messages based on the current game state (e.g., "Do you want to draw a new card?", "You've got Blackjack!", "You're out of the game!").
- **Real-time Updates**: The game updates the card sum and messages dynamically based on player actions.

## Technologies Used

- HTML
- CSS
- JavaScript

## Setup and Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/blackjack-game.git
   cd blackjack-game
## Open the Project

Open the `index.html` file in your web browser to see the app in action.

## Live Demo

Check out the live demo of the application here: [Blackjack Game - Netlify](https://blackjack-game-jonas.netlify.app/). This live demo provides you with a real-time experience of how the application operates.

## Usage

### Start Game:
- Click the "START GAME" button to initialize the game with two random cards.
- The sum of the cards will be displayed, along with a prompt to draw a new card if the sum is less than or equal to 20.

### Draw New Card:
- Click the "NEW CARD" button to draw an additional card.
- The new card will be added to your hand, and the sum will be recalculated and displayed.
- The game will update the message based on the new sum (e.g., whether you have won, lost, or should draw another card).

## Key Takeaways

1. **DOM Manipulation**
   - Learned how to dynamically update HTML content using JavaScript.
   - Used methods like `document.getElementById()` and `textContent` to interact with and update elements on the page.

2. **Event Handling**
   - Gained experience with JavaScript event listeners to handle user interactions, such as button clicks.
   - Implemented functions that are triggered by user actions to control the game flow.

3. **Game Logic Implementation**
   - Developed an understanding of basic game mechanics and how to translate them into code.
   - Created logic for drawing cards, calculating sums, and determining game outcomes (win/lose conditions).

4. **Random Number Generation**
   - Used JavaScript's `Math.random()` function to simulate drawing cards from a deck.
   - Implemented logic to handle different card values and special cases like face cards and aces.

5. **Conditional Statements**
   - Applied conditional logic to manage different game states and outcomes.
   - Used `if-else` statements to control the flow of the game based on the sum of the cards.

6. **CSS Styling**
   - Enhanced the visual appeal of the game using CSS for layout and styling.
   - Learned to use background images, custom fonts, and styling elements to create an engaging user interface.

## Contributing

Contributions are welcome! If you have suggestions or enhancements, please fork the repository and submit a pull request. Your contributions will help improve the functionality and usability of this application.

## License

This project is open source and available under the [MIT License](LICENSE). This license allows you to modify, distribute, and use the application for both private and commercial purposes.
