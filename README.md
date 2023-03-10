# Black-Jack-Game-In-Python
This is a classic implementation of the popular card game, Blackjack, built in Python. The objective of the game is to have a hand value of 21 or as close to 21 as possible without going over.

In this implementation, players can play against a computer dealer and bet with virtual chips. The game begins by shuffling a standard 52-card deck and dealing two cards to the player and two cards to the dealer. The player can see one of the dealer's cards, but the other is face down. The player has the option to "hit" and receive another card or "stand" and keep their current hand. The player can continue to hit until they are satisfied with their hand or until they bust (exceed 21).

Once the player has decided to stand, the dealer will reveal their face-down card and continue to hit until their hand value is 17 or higher. If the dealer busts, the player wins. If the dealer's hand value is higher than the player's without exceeding 21, the player loses. If the player's hand value is higher than the dealer's without exceeding 21, the player wins. If both the player and dealer have the same hand value, it's a tie.

Players can also choose to double their bet and receive one more card or split their hand into two separate hands if they are dealt a pair.

The game is built using Python programming language, and utilizes classes and functions to keep track of the deck, player hand, and dealer hand. It includes user prompts and input validation to ensure smooth gameplay.

# Requirements
This implementation requires Python 3 to be installed on the system.

# How to Play
To start playing the game, simply run the blackjack.py file in your terminal:

# Copy code
python blackjack.py
You will be prompted to enter your name and the number of chips you wish to start with. The game will then begin, and you will be prompted to place a bet before the dealer deals the cards.

# Additional Features
In addition to the basic gameplay, this implementation includes the following features:

Option to double down on a hand
Option to split a hand if dealt a pair
Track and display the player's chip balance


# Acknowledgements
This implementation was built using Python and inspiration was taken from other Blackjack games available online.
