# Family Feud Buzzer

This is a simple browser-based buzzer application inspired by the "Family Feud" game show. Two players compete to buzz in first. One player uses the keyboard's space bar, and the other player uses the mouse's left click button. The first player to buzz in triggers a series of beeps and a flashing indicator on their side. After a short delay, the reset button appears, allowing you to start a new round.

## How It Works

- **Player 1 (Left Side):** Press the **Space Bar** on your keyboard to buzz in.
- **Player 2 (Right Side):** Click the **Left Mouse Button** to buzz in.

The first player to trigger their buzzer is declared the winner. A flashing indicator will appear on the winning player's side, accompanied by a sequence of short beeps.

After the beeps finish, there is a 5-second delay before the "Reset" button is shown. Once available, you can click "Reset" to clear the indicators and start over. Alternatively, pressing **Enter** on the keyboard will also reset the game.

## Additional Features

- **User Interface:**  
  The interface displays instructions and a clear prompt indicating how each player can buzz in. When a winner is declared, the winning message and indicators appear.
- **Visual Indicators:**  
  Each player has a colored bar representing their side of the screen (red for Player 1 and blue for Player 2). The winning player's bar will flash in time with the beeps.
- **Easter Egg:**  
  The word "Friends" includes a tooltip; when hovered over, a small tooltip appears stating "Joe is not your friend."

## How to Run

1. **Download/Clone the Project:**  
   Save the provided HTML file (e.g., `index.html`) to your local machine.

2. **Open in a Browser:**  
   Double-click the `index.html` file or open it in your preferred web browser (e.g., Chrome, Firefox, or Edge).

3. **Play the Game:**

   - **Player 1:** Press Space to buzz in.
   - **Player 2:** Click anywhere on the page to buzz in.

   Once a player wins, wait for the reset button or press Enter to start again.

## Technologies Used

- **HTML** for the structure of the page.
- **CSS** for styling the layout, fonts, colors, and tooltip.
- **JavaScript** for capturing keyboard/mouse events, managing the buzzer logic, playing beeps (via the Web Audio API), and flashing indicators.

## Customization

- You can adjust the colors of the indicators, text, and background by modifying the CSS rules.
- The beep durations, flash timings, and delay before reset are all configurable in the JavaScript section.
- The tooltip and branding can be changed or removed as desired.

## License

This project is provided as-is, with no warranty. Modify and use it freely for personal or educational purposes.
