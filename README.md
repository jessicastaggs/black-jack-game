# Single-Hand Blackjack Game

For this project, I followed along with Scrimba's "Learn JavaScript - Build a Blackjack Game" course and developed a simplified blackjack game (or single-hand blackjack) where the dealer's cards and bidding were removed. The game was focused solely on the player's hand, allowing for a streamlined experience. 


## Features

* Simplified Mechanics: The game was designed to focus only on the player's actions, such as deciding whether to "hit" or "stand" based on the value of their hand, without the complexity of a dealer or bidding system.

* Card Handling: I simulated the drawing of cards, ensured each card had the correct value, and calculated the total score based on standard blackjack rules.

---------------------------------

## Concepts Learned

1. Card Value Calculation:
    * I learned how to simulate the distribution of cards and calculate their values correctly (face cards being worth 10, Aces as 11, and numbers retaining their face values).

2. Game Logic:
    * I practiced how to control the flow of the game with decisions like hitting for a new card.

    * I wrote logic to check if the player's hand went over 21 (busted) and to handle the win/loss condition based on the player's total score.

3. Randomization of Cards:
    * I used randomization through the Math.random() function to simulate shuffling and dealing cards in an unpredictable manner, mimicking a real deck of cards.

4. User Input and Interaction:
    * I incorporated buttons that allowed the player to interact with the game by choosing to "Start Game" or select a "New Card." 

5. DOM Manipulation:
    * I applied skills in manipulating the Document Object Model (DOM) to update the game's interface in real-time, showing card values, player hand totals, and messages such as "Do you want to draw a new card?", "You've got Blackjack!", or "You're out of the game!"

6. Event Handling:
    * I gained experience handling events like button clicks to trigger different actions in the game, such as starting the game and drawing a new card.

7. Conditional Statements:
    * I used 'if' statements to evaluate conditions, such as whether the player busted or got blackjack, as well as if they were still alive and needed to draw another card.

8. Debugging:
    * I also practiced debugging to ensure the game functioned smoothly and handled various scenarios correctly by testing edge cases, such as when the player had a total that was close to 21, starting a new game, drawing cards, and stopping when certain conditions (blackjack or bust) are met.  

---------------------------------

## Upcoming Enhancements

Here are some planned improvements and new features I would love to add to the game in the future:

1. Ace Value (1 or 11):
    * I will update the game logic to properly handle the Ace card value as either 1 or 11 based on the player's hand. If adding 11 would cause the total to exceed 21, the Ace will be counted as 1 instead. 

2. Dealer's Hand:
    * I will add a dealer's hand with a simple rule: the dealer must draw cards until their total reaches at least 17. The game will compare the player's hand to the dealer's to determine the winner. 

3. Betting System:
    * I will implement a betting system where the player starts with a set amount of chips and can place bets before each round. The outcome of the game (win/loss) will affect the player's chips. If the player runs out of chips, the game will end.

4. Game Reset and Multiple Rounds:
    * I will add functionality to allow the game to reset after each round and allow the player to play multiple rounds with updated chips. A "Play Again" button will let players restart the game with a fresh set of cards and chips.

5. User Interface Enhancements:
    * I will improve the user interface by adding better styling, animations, and feedback messages. For example, showing a "You win!" or "You lose!" message and providing visual cues like changing button states when the game is over. 

6. Game History:
    * I will track the player's history, such as the number of rounds played, wins, losses, and remaining chips, and display it on the screen to improve the overall experience. 

---------------------------------

## Instructions to Clone and Run Repository

1. Open the Terminal (for macOS or Linux) or Command Prompt (on Windows).

2. Navigate to the desired directory where you want to clone the repository, use 'cd' command to navigate to directory.

3. Clone the repository. Use 'git clone' command followed by the repository URL to set up repository.

---------------------------------

## Technical Information

The Scrimba "Learn JavaScript - Build a Blackjack Game" course can be found [here.](https://scrimba.com/learn-javascript-c0v)

Image was acquired on [Unsplash.](https://unsplash.com/)
