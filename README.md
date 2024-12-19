# Simon Says Game 🎮

This is a simple implementation of the popular Simon Says memory game. The game generates a random sequence of colored buttons that the player needs to repeat. The game becomes progressively harder as the player advances through levels.

---

## Features
- **Game Start**: The game starts once a key is pressed.
- **Random Sequence Generation**: The game generates a random sequence of colors for the player to repeat.
- **User Input**: The player clicks buttons to replicate the sequence.
- **Level Progression**: Each successful sequence increases the level, making the sequence longer.
- **Game Over**: If the player makes a mistake, the game ends and displays their score.
- **Flashing Effects**: Buttons flash in different colors to indicate the game sequence and user actions.

---

## Key Points
- **Game Sequence**: The game generates a random sequence of colors.
- **User Input Validation**: The user’s input is compared against the game’s sequence.
- **Levels**: The difficulty increases as the player advances, with longer sequences at higher levels.
- **Visual Feedback**: Buttons flash to indicate the current sequence and the user's input.
- **Error Handling**: A game over occurs when the player fails to match the sequence.

---

## How to Play
1. **Start the Game**: Press any key to start the game.
2. **Repeat the Sequence**: The game will show a sequence of colors that you must repeat by clicking the corresponding buttons.
3. **Advancing Levels**: If you successfully repeat the sequence, the game will generate a new, longer sequence.
4. **Game Over**: If you make a mistake, the game will end, showing your score. Press any key to restart.

---

## Technologies Used
- **HTML**: To create the structure of the page and buttons.
- **CSS**: For styling and animations (flashing effects).
- **JavaScript**: To handle the game logic, events, and sequence generation.

---

## Dependencies
No external libraries are used in this game.

---

## How to Use
1. **Clone the Repository**:  
   Clone this repository to your local machine using the following command:  
   ```bash
   git clone https://github.com/eabhishek24/Simon-says.git

## Future Improvements
- Sound Effects: Add sounds for each button press and sequence generation.
- Difficulty Levels: Implement different difficulty settings with varying speeds or colors.
- Scoreboard: Keep track of the highest score and display it on the screen.

## Contributing
Feel free to fork this project and contribute! If you want to suggest improvements or add features, submit a pull request.