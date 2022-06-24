---
publish: true
---
 A 2 player game strategic card game.
 
 # Setup 
 Use Ace-4 in a deck of cards
 - Create a 4 x 3 grid of face up cards and deal each player a hand of 2 cards. Randomly assign each player a color
 
 **Object of the game:** Score as many points as possible. Score points for the value of each card captured.
*eg a captured ace, three and five would be worth 9 points*

# Gameplay
On your turn you may:
- Move a card you control.
- Capture an opponents card.
- Play a card from your hand in an empty space.

## Moving
You may move any card you control (a card that is your color) orthogonally
To do so, swap the card with it's neighbor. If the card has no neighbor, you may not move it to that position.

## Capturing Cards
You may capture an orthogonal neighbor card if:
- It is the enemiy's color
- it is exactly 1 value below the card used to capture it.
- *EXCPETION: ACES CAN CAPTURE FOURS*

To capture a card place it on top of the lower value card and create a stack. When moving with this card now move the entire stack. 

## Playing cards
You may play a card from your hand to any empty space on the grid. You must play all cards in your hand before the end of the game.

# End of the Game
The game ends when both players agree that no more meaningful moves may be made- either when no more moves are possible or no more cards may be captured. All cards must be played from hands.

## Scoring
Add up the value of all the cards of your oponent that you captured. The highest score wins!

![[CaptureCards.csv]]

#game  #game/2player #game/cardGame 