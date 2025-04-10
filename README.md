# Black-jack-game

## 🔍 Game Description:
This is a simple Blackjack (21) card game created using Java Swing and JFrame for the GUI. The game allows a user to play against a computer dealer. The objective is to get a hand total as close to 21 as possible, without going over.

## 🎯 Game Objective:
- Player tries to beat the dealer by getting a hand value closest to 21.
- Cards 2–10 are worth their face value.
- Face cards (J, Q, K) are worth 10.
- Aces can be 1 or 11, depending on which is better for the hand.

## ⚙️ Game Features:
GUI built using Java Swing components (JFrame, JButton, JLabel, etc.).

- User can:
Hit (draw a card)
Stand (end their turn)
Dealer draws until it reaches 17 or more.

- Game displays:
Player and dealer cards
Result (win, lose, draw)

## 📄 How the Game Works (Flow):
Game starts, deck is shuffled.
Both player and dealer get 2 cards (dealer shows 1 card).
Player can Hit (get more cards) or Stand.
If player's hand goes over 21 → Busted!

- After player stands, dealer plays:
Dealer hits until reaching at least 17.

- Compare hands:
Highest hand ≤ 21 wins.
