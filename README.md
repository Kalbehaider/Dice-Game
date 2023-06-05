# Pig Game 🎊 🎊 🎈

This is an implementation of the Pig game based on the tutorial by Jonas Schmedtmann in his JavaScript course.

## Game Rules 🤩⭐

- The game consists of 2 players who play in rounds.
- In each turn, a player can roll the dice as many times as they wish. Each roll adds to the player's ROUND score.
- However, if a player rolls a 1, their ROUND score is lost, and it becomes the next player's turn.
- The player can choose to 'Hold', which adds their ROUND score to their GLOBAL score. After that, it becomes the next player's turn.
- The first player to reach 20 points on the GLOBAL score wins the game.

## Features Implemented 💡🤔

- **Mistaken 'Hold' Prevention**: If the user clicks on 'Hold' before rolling the dice, an alert message notifies the player about the error and prompts them to roll the dice.
- **Leaderboard**: A leaderboard is displayed on the page, showcasing the overall best player scores.
- **Player Sessions**: Players can log in to view their personal records and achievements.
- **Two Dice**: The game can be played with two dice instead of one for added excitement.
- **Losing Score on Double Six**: If a player rolls two sixes, their score is reset, and it becomes the next player's turn.
- **Customizable Winning Score**: Players can set their own winning score, allowing flexibility in game length.
- **Responsive Design**: The game is responsive and optimized for mobile devices.
