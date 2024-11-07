# Bulls and Cows Game 🎮

## How to Play

### 🎯 Objective
The objective of the Bulls and Cows game is to guess a secret 4-digit number. Each digit in the number is unique.

### 🖥️ Game Interface
1. **Heading**: The game displays a heading "Guess the 4-digit Number".
2. **Number of Tries**: Below the heading, the remaining number of tries is displayed.
3. **Input Field**: An input field is provided to enter your 4-digit guess.
4. **Check Button**: A button labeled "Check" is available to submit your guess.
5. **Result Display**: The result of your guess (number of bulls and cows) is displayed below the button.

### 🕹️ Steps to Play
1. **Initial Setup**: The game generates a random 4-digit number with unique digits. The player starts with 5 tries.

2. **Entering a Guess**:
    - Enter a 4-digit number into the input field.
    - Ensure the number has no repeated digits and is between 1000 and 9999.

3. **Checking the Guess**:
    - Click the "Check" button to submit your guess.
    - The game will validate your input. If the guess is invalid (contains repeated digits or is not a 4-digit number), an alert will prompt you to enter a valid guess.

4. **Interpreting Results**:
    - After a valid guess, the game will provide feedback in the form of "bulls" and "cows":
        - **Bulls** 🐂: Digits in your guess that are in the correct position.
        - **Cows** 🐄: Digits in your guess that are in the secret number but in the wrong position.
    - The result will be displayed below the "Check" button.

5. **Winning the Game** 🎉:
    - If your guess has 4 bulls (all digits in the correct positions), you win the game.
    - An alert will congratulate you, and the game will reload for a new round.

6. **Losing the Game** ❌:
    - Each incorrect guess reduces the number of tries by 1.
    - The remaining tries are updated and displayed.
    - If you run out of tries without guessing the number, the game ends.
    - An alert will inform you of the game over and reveal the secret number. The game will then reload for a new round.

### 📝 Example
1. You enter the guess "1234" and click "Check".
2. The game checks the guess against the secret number.
3. Suppose the secret number is "4321". The feedback might be "0 bulls, 4 cows" (since all digits are correct but in the wrong positions).
4. You enter another guess and repeat the process until you either guess the number correctly or run out of tries.

### 📌 Notes
- The secret number is randomly generated each time the game reloads.
- Always enter a valid 4-digit number with unique digits to ensure the game functions correctly.

Enjoy playing! 🚀
