# Blackjack-Game
This is a GUI-based Blackjack game implemented in Python which is originally a classic casino game of luck and strategy.
The game is based on the description provided in the wikipedia. The objective of the game is to beat the dealer, which can be done in the following ways:

• Get 21 points on the player's first two cards (called a blackjack), without a dealer blackjack<br>
• Reach a final score higher than the dealer without exceeding 21 or<br>
• Let the dealer draw additional cards until his or her hand exceeds 21.<br>

The game is implemented with standard 1 deck of cards (Set of 52 cards).It has implementation of two standard options for player after receiving two initial cards: Hit and Stand. The rules for each implementation is described below:<br>
•	Hit: Take another card from dealer<br>
•	Stand : Player takes no more cards and dealer draws the card.<br>

Following rules are implemented for the dealer in the game.<br>
•	Dealer hits until his cards total 17 or more points.<br>
•	Dealer also hits on soft 16(i.e, when the dealer initial 2 card value is 16,  e.g., an initial ace and five).<br>

# Running the game
Download the folder, install necessary modules and run the Run.py file containing source code.<br>
`python3 Run.py`

# Playing Cards
A standard deck of playing cards has four suits (Hearts, Diamonds, Spades and Clubs) and thirteen ranks (2 through 10, Ace card, then the face cards - Jack, Queen, King) for a total of 52 cards per deck. Jacks, Queens and Kings all have a rank of 10. Aces have a rank of either 1 or 11 as needed to reach 21 without busting. 

