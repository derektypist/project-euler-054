# Project Euler 054 - Poker Hands

In the card game poker, a hand consists of five cards and are ranked, from lowest to highest, in the following way:

- **High Card:** Highest Value Card
- **One Pair:** Two cards of the same value
- **Two Pairs:** Two different pairs
- **Three of a Kind:** Three cards of the same value
- **Straight:** All cards are consecutive values
- **Flush:** All cards of the same suit
- **Full House:** Three of a kind and pair
- **Four of a Kind:** Four cards of the same value
- **Straight Flush:** All cards are consecutive values in same suit
- **Royal Flush:** Ten, Jack, Queen, King, Ace in same suit

The cards are valued in the order:
2, 3, 4, 5, 6, 7, 8, 9, 10, Jack, Queen, King, Ace

If two players have the same ranked hands then the rank made up of the highest value wins; for example a pair of eights beats a pair of fives.  But if two ranks tie, for example, both players have a pair of queens, then highest cards in each hand are compared; if the highest cards tie then the next highest cards are compared, and so on.

The array contains one-thousand random hands dealt to two players.  Each line of the file contains ten cards (separated by a single space): the first five are Player 1's cards and the last five are Player 2's cards.  You can assume all hands are valid (no invalid characters or repeated cards), each player's hand is in no specific order, and in each hand there is a clear winner.

How many hands does player 1 win?

Information at [Project Euler 054](https://projecteuler.net/problem=54)

## UX

**Getting Started**

Select Show Solution to show the solution.  Select Hide Solution to hide the solution.  You can also view detailed instructions with examples of the five hands dealt to two players and the random hands dealt to two players.

**User Stories**

As a user, I can show or hide the solution by selecting the appropriate button

As a user, I can view more detailed instructions

As a user, I can view the random hands dealt to two players

As a user, I expect `pokerHands(handsArr)` to return a number.

As a user, I expect `pokerHands(handsArr)` to return 376.

**Information Architecture**

The function `pokerHands(arr)` returns a number, where `arr` is a string array.

## Features

Allows the user to show or hide the solution as described in [Project Euler 054](https://projecteuler.net/problem=54).  Also allows the user to view the random hands and detailed instructions (including examples of hands).

## Technologies

Uses HTML5, CSS3, JavaScript, Bootstrap 5.2.2 and Google Fonts.

## Testing

Ensure all user stories have been met.

## Deployment

Deployed on [GitHub Pages](https://derektypist.github.io/project-euler-054) at the main branch.

## Credits

### Content

Code in script.js taken from [Mike Talbot - Real World JavaScript map/reduce - Solving the Poker Hand Problem](https://dev.to/miketalbot/real-world-javascript-map-reduce-solving-the-poker-hand-problem-3eie), which was accessed on March 2022.

### Acknowledgements

- [Project Euler](https://projecteuler.net)
- [Mike Talbot](https://dev.to/miketalbot/real-world-javascript-map-reduce-solving-the-poker-hand-problem-3eie)
- [FreeCodeCamp](https://www.freecodecamp.org)