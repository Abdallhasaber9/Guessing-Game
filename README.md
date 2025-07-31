# Guessing-Game
🎮 Guessing Game – Project Description
📌 Game Idea:
A simple number guessing game where the player tries to guess a hidden number randomly selected by the system.
The player chooses a difficulty level, and then attempts to guess the number within a limited number of tries.
Hints are provided such as "Increase the number" or "Decrease the number", and the player can choose to play again after each round.

🧠 How to Play:
When the game starts, a welcome message appears and the user is prompted to choose from 3 difficulty levels:

Difficulty	Range	Attempts
🟢 Easy	1 to 10	5 tries
🟡 Medium	1 to 100	10 tries
🔴 Hard	1 to 1000	20 tries

After selecting a level, a random number is generated within the corresponding range.

The player enters guesses one by one:

If the guessed number is less than the target → "No, Increase!"

If the guessed number is greater than the target → "No, Decrease!"

If correct → "You got it successfully in X trials!"

If out of attempts → the correct number is revealed.

After each round, the game asks:

text
Copy
Edit
Do you want to play again? (y/n)
If the user types y → a new round starts.

If the user types n → the game ends with a thank-you message.

⚙️ Functions Used:
Function	Purpose
show_levels()	Display difficulty level options
game_level_choice()	Read and validate user difficulty choice
set_game_settings(level)	Set range and number of attempts
start_play(range, attempts)	Run the main guessing loop
play_again()	Ask if user wants to restart
play()	Manage the full game flow

✅ Game Features:
Interactive CLI using input() and print()

Multiple difficulty levels for varied challenges

Option to replay multiple rounds

Clear instructions and responsive feedback

Modular structure for easy modification or upgrades


