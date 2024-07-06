# Blackjack Game

## Description
This is a command-line Blackjack game developed in C++. The game allows users to place bets, hit or stand, and view their cards and balance. The game features balance persistence, ASCII art for a better visual experience, and a special prize when a certain balance is reached.

## Features
- Simulates a real Blackjack game with card drawing and hand value calculations.
- Betting system allowing users to place bets before each round.
- Balance persistence using file I/O, so users can resume their game later.
- ASCII art for cards to enhance the user experience.
- Secret prize feature that awards a "Bitcoin" when the balance reaches $5000.
- Automatic balance reset to $1000 if the balance drops to $0.

## Technologies Used
- C++
- Standard Library: `iostream`, `vector`, `cstdlib`, `ctime`, `fstream`

## How to Play
1. Clone the repository:
    ```sh
    git clone https://github.com/akaseb05/BlackJack.git
    ```
2. Navigate to the project directory:
    ```sh
    cd blackjack-game
    ```
3. Compile the code:
    ```sh
    g++ -o blackjack blackjack.cpp
    ```
4. Run the game:
    ```sh
    ./blackjack
    ```

## Game Rules
- The game follows standard Blackjack rules.
- The player starts with a balance of $1000.
- The player can place bets, hit or stand, and try to beat the dealer's hand without exceeding 21.
- If the player's balance reaches $0, it will automatically reset to $1000.
- A special prize of a "Bitcoin" is awarded when the player's balance reaches $5000.

## Save Progress
- The game saves your balance to a file called `balance.txt`.
- If you leave the game and come back later, your balance will be loaded from this file, allowing you to resume where you left off.
- The balance is updated and saved at the end of each round.

## Example Output
Welcome to Blackjack! You start with $1000.

You have $1000. Enter your bet: 100

Player's cards: A 10 (Sum: 21)

Dealer's cards: 8 ? (Sum: 8 + ?)

Do you want to hit (h) or stand (s)? s

Dealer's cards: 8 9 (Sum: 17)

You win!

You now have $1100.

Do you want to play again? (y/n) or reset your balance (r):


## ASCII Art
ASCII Art resembling read cards in BlackJack

## Contributing
Feel free to submit issues or pull requests if you have suggestions or improvements.

## Contact
For any questions or feedback, please visit [My GitHub profile](https://github.com/akaseb05).
