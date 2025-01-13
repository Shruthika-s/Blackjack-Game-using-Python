# Blackjack Game

This is a simple implementation of the classic card game **Blackjack** written in Python.

## Features:
- A text-based version of Blackjack with a simple and easy-to-understand gameplay.
- Play against the computer.
- Automated card dealing, scoring, and game flow logic.

## Files:
1. **BlackJack.py**: Contains the core logic of the Blackjack game including functions for dealing cards, calculating scores, comparing results, and handling user input.
2. **art.py**: Contains ASCII art to display the logo and styling for the game.

## Gameplay:
- The game starts with the user and computer receiving two cards.
- The user can decide to draw more cards or pass.
- The computer automatically draws cards until it reaches a score of at least 17.
- The result is displayed based on the final scores.

## How to Play

1. Run the `BlackJack.py` script.
2. Follow the prompts to play the game:
   - Type 'y' to get another card.
   - Type 'n' to pass your turn.
3. The game continues until either you or the computer reaches a conclusion (Blackjack, draw, or loss).
  
## Rules:
- The goal of the game is to get a card total as close to 21 as possible without going over.
- A hand total of 21 with the first two cards results in an instant win (Blackjack).
- A score over 21 means you lose automatically.
